---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Addressing Fairness in Classification with a Model-Agnostic Multi-Objective
  Algorithm
subtitle: ''
summary: ''
authors:
- Kirtan Padh
- Diego Antognini
- Emma Lejal Glaude
- Boi Faltings
- Claudiu Musat
tags: []
categories: []
date: '2020-01-01'
lastmod: 2020-11-30T20:40:16+01:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-11-30T19:40:16.527725Z'
publication_types:
- '3'
abstract: 'The goal of fairness in classification is to learn a classifier that does not discriminate against groups of individuals based on sensitive attributes, such as race and gender. One approach to designing fair algorithms is to use relaxations of fairness notions as regularization terms or in a constrained optimization problem. We observe that the hyperbolic tangent function can approximate the  indicator function. We leverage this prop-erty to define a differentiable relaxation that approximates fairness notions provably better than existing relaxations. In addition, we propose a model-agnostic multi-objective archi-tecture that can simultaneously optimize for multiple fairness notions and multiple sensitive attributes and supports all statistical parity-based notions of fairness. We use our relaxation with the multi-objective architecture to learn fair classifiers. Experiments on public datasets show that our method suffers a significantly lower loss of accuracy than current debiasing algorithms relative to the unconstrained model.'
publication: '*arXiv preprint arXiv:2009.04441*'
---
