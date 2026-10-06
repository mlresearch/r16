---
abstract: Predictive models can fail to generalize from training to deployment environments
  because of dataset shift, posing a threat to model reliability in practice. As
  opposed to previous methods which use samples from the target distribution to reactively
  correct dataset shift, we propose using graphical knowledge of the causal mechanisms
  relating variables in a prediction problem to proactively remove variables that
  participate in spurious associations with the prediction target, allowing models
  to generalize across datasets. To accomplish this, we augment the causal graph
  with latent counterfactual variables that account for the underlying causal mechanisms,
  and show how we can estimate these variables. In our experiments we demonstrate
  that models using good estimates of the latent variables instead of the observed
  variables transfer better from training to target domains with minimal accuracy
  loss in the training domain.
title: 'Counterfactual Normalization: Proactively Addressing Dataset Shift Using Causal
  Mechanisms'
year: '2018'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: subbaswamy18a
month: 0
tex_title: 'Counterfactual Normalization: Proactively Addressing Dataset Shift Using
  Causal Mechanisms'
firstpage: 946
lastpage: 956
page: 946-956
order: 946
cycles: false
bibtex_author: Subbaswamy, Adarsh and Saria, Suchi
author:
- given: Adarsh
  family: Subbaswamy
- given: Suchi
  family: Saria
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
pdf: https://raw.githubusercontent.com/mlresearch/r16/main/assets/subbaswamy18a/subbaswamy18a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
