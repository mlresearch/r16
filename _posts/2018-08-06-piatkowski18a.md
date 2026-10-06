---
abstract: Recent stochastic quadrature techniques for undirected graphical models
  rely on nearminimax degree-k polynomial approximations to the model’s potential
  function for inferring the partition function. While providing desirable statistical
  guarantees, typical constructions of such approximations are themselves not amenable
  to efficient inference. Here, we develop a class of Monte Carlo sampling algorithms
  for efficiently approximating the value of the partition function, as well as the
  associated pseudo-marginals. More precisely, for pairwise models with n vertices
  and m edges, the complexity can be reduced from O(dk) to O(k4 + kn + m), where d
  $\geq$4m is the parameter dimension. We also consider the uses of stochastic quadrature
  for the problem of maximum-likelihood (ML) parameter estimation. For completely
  observed data, our analysis gives rise to a probabilistic bound on the log-likelihood
  of the model. Maximizing this bound yields an approximate ML estimate which, in
  analogy to the momentmatching of exact ML estimation, can be interpreted in
  terms of pseudo-moment-matching. We present experimental results illustrating the
  behavior of this approximate ML estimator.
title: Fast Stochastic Quadrature for Approximate Maximum-Likelihood Estimation
year: '2018'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: piatkowski18a
month: 0
tex_title: Fast Stochastic Quadrature for Approximate Maximum-Likelihood Estimation
firstpage: 714
lastpage: 723
page: 714-723
order: 714
cycles: false
bibtex_author: Piatkowski, Nico and Morik, Katharina
author:
- given: Nico
  family: Piatkowski
- given: Katharina
  family: Morik
date: 2018-08-06
note: Reissued by PMLR on 04 October 2026.
address:
container-title: Proceedings of the 34th Conference on Uncertainty in Artificial Intelligence
volume: R16
genre: inproceedings
issued:
  date-parts:
  - 2018
  - 8
  - 6
pdf: https://raw.githubusercontent.com/mlresearch/r16/main/assets/piatkowski18a/piatkowski18a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
