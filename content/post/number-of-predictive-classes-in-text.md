---
title: "Number of predictive classes you can find in text"
date: 2008-04-17
draft: false
tags: ['compression', 'linguistics', 'paradigmatic-classes', 'hutter-prize']
categories: ["articles"]
summary: "Analysis of how paradigmatic distributions in text create numerous but overlapping classes that govern random syntax."
---

From a discussion on the "Hutter-Prize" Google group:

...If A_1, A_2,... A_n
are the contexts of A in some text, and X_1, X_2,...X_n are contexts of
other tokens, then the number of ways A can have common contexts with
other tokens in the text, and thus uniquely specify some new
paradigmatic class, are just Matt's "(n choose k) = n!/(k!(n-k)!)
possible sets", where k is the number of common contexts between A and
some other token.

The syntagmatic distribution of sequences AX_? specified by these
classes in the text can be random, because many different paradigmatic
distributions (A_i,...A_i+k) can be equally likely (and must be,
because many of the "n choose k" possible classes will overlap, and
thus form complementary distributions with each other??) But the
relationship between any given syntax and its corresponding
paradigmatic distribution is not random. And the different paradigmatic
distributions (knowledge?) governing that random syntax are not random
either, just very numerous. Much more numerous than the sequence of 2n
or so tokens needed to specify them.