# Introduction

## History

A polemic $$$Pronounced peh-lem-ick, not pole-mick, which should hopefully save
you a similar sort of embarrassment that I had suffered $$$ is an argument which
as directly as possible, makes claims to support ones own position and undermine
an opposing one. The word describes more a stylistic decision than a specific
form of rhetoric. It's aggressive and, as per the etymology, warlike. The style
is old being pioneered by the Greeks and vaguely adopted by prophetic Hebrews.
Though not the point at hand, I would also argue it should be counted amongst
the few cultural results of the Roman empire, the other two being satires and
the aesthetic of western empire, considering the impact of The Philippic.

The polemic has survived and in fact been lionized in modern times. I would go
as far as to say that a great deal of modern published editorials could be
argued to be polemical.

## Motivation

As a personal motivation, I spend a great deal of time on the internet and a
great deal of that time is spent doing something approximating software
engineering. I think it is important to understand the culture one is immersed
in, and if that culture presents itself primarily as blogs, email chains, and
comments on hacker news, then we should engage it as such. $$$ Frankly, I'm just
interested in people, and I would like others to at least understand a genre of
rhetoric I spend a lot of time engaging with. In this way, this is apologia of
the programmer polemical $$$

As for why _you_ should care: for better or for worse, the professional culture
of the yuppie silicon valley tech-penuer has become the culture of one of the
largest financial sectors in the world.

> insert here some statistics about the size of the tech industry

The behavior and output of this culture has massive economic effect. Though we
should hope for our engineering decisions to have some objective through line,
we should not discount the effect of rhetoric on our decisions: after all, how
often do you consult reddit prior to choosing a library?

Take also the fact that the tech industry, as it were, is somewhat defined
_culturally_; Amazon brokers physical goods, Tesla makes cars, Google is an
advertising company, Netflix is a _media production company_. What unifies these
companies is sometimes geographic proximity, in itself an element of culture to
be sure, but in reality "tech company" is a shorthand for a loose collection of
professional cultural practices.

I present a chronology of one aspect of this culture, the programmer polemical.
I will provide a few examples of the genre, attempt to contextualize and provide
commentary for those polemics, and hopefully explore an under-recognized
subculture.

## A Brief Note

While I will avoid strictly defining the programmer polemic, since too stringent
a criteria will obscure the actual value of the following pieces too much I
think, we will require that each piece _must_ be directly relating to software
and hardware engineering and the practice thereof. The article needs to be about
_making_ the technology, the details of the implementation, and more to the
point how technology _should_ be made, and not about the _technology itself_ or
how it should be used. These are articles written almost exclusively _for other
programmers_.$$$I will be prefixing various nouns as _programmer_-X when I am
trying to convy this character, a la, _gentleman-historian_$$$

This immediately eliminates a lot of the rationalist milieu, the LessWrong, MIRI
crowd, who frankly deserve their own investigation. They're a fascinating group
of people, although maybe not in the way that they thing they are fascinating,
but are ultimately out of scope for this conversation. As such, we will not be
discussing anything longtermism, growth-hacking related.

While we're in the brief note section, I'll also make a promise to try to make
the technical concepts within grasp for a non programmer audience. As a result,
if you know a thing or two about programming, you might find some long
paragraphs very boring.

> this is a different section entirely

Software engineering sometimes attracts a particular personality; as a software
engineer you have been granted a small fiefdom of bits on which any arbitrary
rules can be executed. Other engineering professions, almost as a rule, have to
contend with physical realities and limitations, in this sense, the software
engineer has been granted a domain with more degrees of freedom.

# The Subsidized Crib of Tech

Bridges preced the Euler-Bernoulli beam theory by give or take six thousand
years. It took an additional 150 years after their discovery before the theory,
and the results of mathematical analysis writ large, were incorporated into the
discipline of engineering. More traditional engineering discplines than software
engineering often have a culture which preceds their modern tools.

Software engineering, save for the last decade or so, has owed signficant
portions of both it's tools and it's culture to the academic substrate it
emerged from. Research at various public universities such as [list of unis] and
research institutions recieving public funds such as [Bell etc] created the
foundation of the modern tech sector.

> History of modern computing appended to last paragraph

The most idealistic version of the espirt de corp of publicaly funded research
institutions is collaborative; think of how, for example, DARPA net's primary
use was email, rather than resource pooling as it was intended for. Research
happend with an open door because, after all, it was the public which was
funding it. Research funded in this manner is subject to rhetoric and internal
politics in a way that private engineering never is. That semi-political culture
was inhereted by early software engineers.

## Considered Harmful

I choose to credit Dijkstra for at least popularizing public debate as a medium
of technical discussion, if he wasn't the first he surely was the best of his
time. Published in the March 1968 of edition of Communications of the ACM,
"Go-To Statement Considered Harmful" is a outright decry of the use of go-to
statements.

A go-to statement, at least the version he discusses, is an instruction which
takes a number $n$ and executes the program from line $n$.

The argument progresses as follows:

- Assertion: Humans do better working with static relations than dynamic
  processes
- Given a program, consider how we track *where* the program is, lets call the
  data that allows us to place where we are in a program *coordinates*.
- Certain programming constructs, like loops or conditionals, require us to
  track our coordinates both dynamicly and statically. This is because we can
  only interpret a variable with respect to its progress in the program
- go-to statements *make it difficult to ascertain where in the program a piece
  of code is executed*, that is, go-to statements obscure the coordinates we
  need to reason about a program
- go-to make the program execution much more dynamic and difficult to parse, as
  asserted, we as humans should avoid relying on go-to to structure our
  programs.

The specific go-to he's talking about is ALGOL 60's, which (in)famously could
jump anywhere else in the code. The modern version of go-to is typically the
what the C programming language came up with, where you must specify a jump
location with a label, a convention that began in no small part due to this
article. Overtime, different constructs such as break, continue, and even
*return* were created as essentially limited forms of the go-to.

How do we

## RFCs

## Worse is better is worse is worse is better ...

# Romulus and Remus

# OOP and Other Poorly Defined Concepts

# AI is Dead, Long Live AI

# Briefly, Mathematics

# Conclusion
