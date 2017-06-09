---
layout: post
title: Benchmarking libsemigroups
subtitle: by Julius Jonu&#353;as and James Mitchell
mdate: October 19, 2016
---

In this post we present some performance benchmarks for the
[libsemigroups](https://james-d-mitchell.github.io/libsemigroups/index.html)
C++ library for semigroups and monoids. In particular, we present some
experimental data about the performance of the
[add_generators](https://james-d-mitchell.github.io/libsemigroups/classlibsemigroups_1_1_semigroup.html#a7a8af8615e4a45aa6e83837f01baa5a2)
method of the
[Semigroup](https://james-d-mitchell.github.io/libsemigroups/classlibsemigroups_1_1_semigroup.html)
class, and the parallel version of the [Froidure-Pin
algorithm](https://www.irif.fr/~jep/PDF/Rio.pdf) described in our recent paper:

> J. Jonusas, J. D. Mitchell, and M. Pfeiffer,
> &#8216;Two variants of the Froiduire-Pin Algorithm for finite
> semigroups&#8217;, submitted; [https://arxiv.org/abs/1704.04084](https://arxiv.org/abs/1704.04084)
