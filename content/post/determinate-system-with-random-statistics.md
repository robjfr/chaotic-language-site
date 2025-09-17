---
title: "Determinate system with random statistics"
date: 2008-04-17
draft: false
tags: ['AI', 'NLP', 'randomness', 'complexity', 'compression']
categories: ["articles"]
summary: "Discussion of how determinate relational distributions can produce random language statistics while maintaining systematic structure."
---

From a thread on the comp.compression discussion list, 2007:

I think the insight we have been looking for to model AI/NLP is that
the information needed to code different ways of ordering a system
(knowledge) is always greater than the information to code the system
itself (for a random system.)

In the context of AI/NLP it is important to note that random need not
mean indeterminate. I hope I demonstrated this in our earlier thread on
comp.compression. In the case of language relational distributions can
precisely determine a syntax which nevertheless has random statistics.
To be clear I am talking once again about our toy example:
"AX...DX...DB...AZ...YZ...YC...A_". Here different relational
distributions (A,D), (A,Y) (corresponding to "knowledge": in some ways
"A is close to D but not Y" but in other ways "A is close to Y but not
D"?) deterministically specify syntax, but still produce a random
language model A_ -> AB/AC (probably because the distributions are
contradictory.)

These distributions specify the system, but it is more expensive to
enumerate all the different possible relational distributions than it
is to enumerate the system itself. (So they can't be used to compress
it.)