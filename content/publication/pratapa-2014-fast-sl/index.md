---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Fast-SL: An efficient algorithm to identify synthetic lethal reaction sets
  in metabolic networks'
subtitle: ''
summary: ''
authors:
- Aditya Pratapa
- Shankar Balachandran
- Karthik Raman
tags:
- '"genome-scale metabolic-networks myown synthetic-lethality"'
categories: []
date: '2014-07-01'
lastmod: 2020-10-31T20:24:44+05:30
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
publishDate: '2020-10-31T15:04:36.805219Z'
publication_types:
- '0'
abstract: Synthetic lethal reaction/gene-sets are sets of reactions/genes where only
  the simultaneous removal of all reactions/genes in the set abolishes growth of an
  organism. In silico, synthetic lethal sets can be identified by simulating the effect
  of removal of gene sets from the reconstructed genome-scale metabolic network of
  an organism. Flux balance analysis (FBA), based on linear programming, has emerged
  as a powerful tool for the in silico analyses of metabolic networks. To identify
  all possible synthetic lethal reactions combinations, an exhaustive sampling of
  all possible combinations is computationally expensive. We surmount the computational
  complexity of exhaustive search by iteratively restricting the sample space of reaction
  combinations for search, resulting in a substantial reduction in the running time.
  We here propose an algorithm, Fast-SL, which provides an efficient way to analyse
  metabolic networks for higher order lethal reaction sets. Fast-SL offers a substantial
  speed-up through a massive reduction in the search space for synthetic lethals;
  in the case of E. coli, Fast-SL reduces the search space for synthetic lethal triplets
  by over 4000-fold. Fast-SL also compares favourably with SL Finder, an algorithm
  for identifying synthetic lethal sets, by Suthers et al (2009), which involves the
  solution of a bi-level Mixed Integer Linear Programming problem. We have implemented
  the Fast-SL algorithm in MATLAB, building upon COBRA toolbox v2.0.
publication: ''
url_pdf: http://arxiv.org/abs/1406.6557v2
---
