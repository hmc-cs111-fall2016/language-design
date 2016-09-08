[Teams]: https://github.com/hmc-cs111-fall2016/language-design/wiki/Teams
[BetterDesign]: https://www.fastcodesign.com/1665735/why-arent-computer-programming-languages-designed-better
[APIPDF]: https://dl.acm.org/citation.cfm?id=1176617.1176622&coll=DL&dl=GUIDE&CFID=372348918&CFTOKEN=51331222
[APITalk]: https://www.youtube.com/watch?v=aAb7hSCtvGw
[GrowPDF]: https://www.cs.virginia.edu/~evans/cs655/readings/steele.pdf
[GrowTalk]: https://www.youtube.com/watch?v=_ahvzDzKdB0
[WhenAndHow]: http://dl.acm.org/citation.cfm?id=1118892
[AppleScript]: https://dl.acm.org/citation.cfm?doid=1238844.1238845
[WhatIsGray]: http://lea.verou.me/2014/07/an-easy-notation-for-grayscale-colors/
[LanguageStereotypes]: https://modelviewculture.com/pieces/c-is-manly-python-is-for-n00bs-how-false-stereotypes-turn-into-technical-truths
[aRrgh]: http://arrgh.tim-smith.us/
[Perl]: https://dl.acm.org/citation.cfm?id=2089159&CFID=578519747&CFTOKEN=43192998

# Language Design
###### _Submission deadline: Wednesday, Sept. 14 at 11:59pm_
###### _Critique deadline: Friday, Sept. 16 at 11:59pm_

In this assignment, we'll focus language design. The goals are to:

   + find ideas that are new and interesting to you or which are presented in
   new and interesting ways
   + identify good and bad practices for language design
   + understand more about the benefits and drawbacks of DSLs
   + challenge your currently held beliefs about programmers and programming 
   languages

To do so, you'll read about language design, then answer some questions, citing
the readings as evidence.

## Teamwork
This assignment requires you to work with one other person. Each of you must
read the papers and contribute to the ideas and effort of the responses (more
details below).

**[Fill in this table with the members of your team][Teams].**

Only one team member needs to fork this repository.

## The Readings
Here are the readings, in their recommended (but certainly not required!) order.

   1. [_Growing a Language_][GrowPDF] by Guy Steele
      + cite as: [Steele, 1998]
      + This one starts out a little weird, but hang with it. 
   1. [_Why Aren't Computer Programming Languages Designed Better?_][BetterDesign] 
   by John Pavlus
      + cite as: [Pavlus, 2012]
   1. [_How to Design a Good API and Why It Matters_][APIPDF]* by Joshua Bloch
      + cite as: [Bloch, 2006]
      + There is also a [talk][APITalk], which expands on the tips in the 
      reading and provides lots more detail. Feel free to use the talk to
      understand this material better, or as extra supporting material. If you
      cite the talk, cite it as [Bloch, 2007] *and* provide [a link to the time at 
      which the material you cite occurs](http://www.wikihow.com/Link-to-a-Certain-Time-in-a-YouTube-Video).
   1. [_An Easy Notation for Grayscale Colors_][WhatIsGray] by Lea Verou
      + cite as: [Verou, 2014]
      + An interesting post on how to choose a name for _one_ feature of an
      API. The comments are a good source of additional material.
   1. [_C is Manly, Python is for “n00bs”: How False Stereotypes Turn Into 
       Technical "Truths"_][LanguageStereotypes] by Jean Yang & Ari Rabkin
      + cite as: [Yang and Rabkin, 2015]

_*This paper belongs to the Association for Computing Machinery's digital
library. You should be able to access them from any computer on the Claremont
Colleges' network. If you have trouble accessing, please post on Piazza._

Each reading also describes how to cite it. For example, if you are going to
cite the Steele paper in your responses, you might write something like:

 > "Domain-specific languages are the best thing ever, except for taking a class
 > *about* domain-specific languages, which is better than petting unicorns" 
 > [Steele, 1998]. 

_(not an actual quote)_

## The Responses

After completing the readings, answer the questions in `language-design.md` 
(see the suggestions below for how to approach the writing).

## Grading

Good responses (i.e., responses that receive a 3) will:

   + state a clear opinion
   + support the opinion with evidence from the readings, cited properly
   + be well-written, i.e., clear yet concise using good spelling, grammar, and
   organization to convey a well-formed idea
   + be the result of teamwork. A response can have
   multiple opinions, e.g., if the two of you disagree about something. The only
   requirement is that the response contain the ideas and efforts of both
   partners.

Great responses (i.e., responses that receive a 4) will go a bit beyond, e.g.,
by using (and citing) a source outside of the readings. Here are some excellent 
additional readings:
   + [_When and How to Develop Domain-Specific Languages_][WhenAndHow]* by
   Marjan Mernik, Jan Heering, and Anthony M. Sloane
      + cite as: [Mernik _et al._, 2005]
      + Of most interest might be sections 1 and 2.
   + [_aRrgh: a newcomer’s (angry) guide to R_][aRrgh] by Tim Smith
      + cite as: [Smith, 2016]
   + [_An empirical comparison of the accuracy rates of novices using the quorum, perl, and randomo programming languages_][Perl]* by Andreas Stefik, Susanna Siebert, 
   Melissa Stefik, and Kim Slattery
      + cite as: [Stefik _et al._, 2011]
      + Raises the question: Is Perl's syntax design any better than a randomly
      designed syntax?

_*These papers belong to the Association for Computing Machinery's digital
library. You should be able to access them from any computer on the Claremont
Colleges' network. If you have trouble accessing, please post on Piazza._

These readings take various forms, including peer-reviewed, academic papers 
and popular-press articles. 

## Suggestions for working on the assignment

Although the responses should be clear and cite evidence, they do not need to 
be formal. It's fine to say "Jordan believes *A* because *X*. Napur disagrees
because *Y*." (where Jordan and Napur are the two people writing the response).

Here are some suggestions for how to work on this assignment. Following these
suggestions should produce good work; but you will be graded on your work, not
on whether you followed these suggestions. (In particular, we won't be grading
based on word count. We'll be grading on whether the work satisfies the criteria
above.)

   1. Do the readings together or separately, your choice. Either way, discuss
   things that interested you both or that one or both of you doesn't yet
   understand.
   1. Read over the questions you'll be answering.
   1. Working together, draft an outline of your response. The outline should be
   at the pseudocode level, i.e., clear enough that someone writing the full
   version doesn't have to make significant decisions about what to write.
   1. Draft an initial version of the response. You don't have to do this
   together. If the outline is sufficiently specific *and* it contains both your
   ideas, you can divvy up the writing responsibilities. A good response will
   probably be 250-500 words (shorter for the questions with smaller scope, 
   longer for the more open-ended questions).
   1. Iterate until you're satisfied. 

## Peer-review
After the submission deadline, read over your critique partners' work. You can 
(and probably should) split up the critiquing. It's not necessary for both of
you to comment on *all* of their work; but all of their work should be
covered between the two of you. You don't need to work on the critiques together,
 although you certainly can. In any case, your critique grade will be based on
 your individual contribution.

Here are some suggestions for critiques:

   + Find something in their work that interests you, and engage in that.
   + Did they have a different opinion than you? If so, have they changed your
mind? How so?
   + Did they have the same opinion as you? If so, did they support it in the
   same way that you did (e.g., using the same sources). Do you have any
   additional evidence that might bolster their claim / opinion?
   + Did they mention part of the readings that you had missed, but which you
   find interesting? In what way does it relate to the work that you submitted?
   + Is their idea / opinion clear? Is it novel to you? Let them know! 
   If the work is not clear, which aspect is unclear? How could they help you
   understand better?


## Tasks
- [ ] Form partners and [record your team on the wiki][Teams].
- [ ] Read all the things.
- [ ] Write all the responses.
- [ ] Submit your work.
- [ ] Comment on your critique partners' work.
