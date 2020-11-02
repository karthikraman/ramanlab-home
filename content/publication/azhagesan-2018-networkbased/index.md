---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Network-based features enable prediction of essential genes across diverse
  organisms
subtitle: ''
summary: ''
authors:
- Karthik Azhagesan
- Balaraman Ravindran
- Karthik Raman
tags:
- '"myown"'
categories: []
date: '2018-12-01'
lastmod: 2020-10-31T20:24:42+05:30
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
publishDate: '2020-10-31T15:04:35.548085Z'
publication_types:
- '2'
abstract: Machine learning approaches to predict essential genes have gained a lot
  of traction in recent years. These approaches predominantly make use of sequence
  and network-based features to predict essential genes. However, the scope of network-based
  features used by the existing approaches is very narrow. Further, many of these
  studies focus on predicting essential genes within the same organism, which cannot
  be readily used to predict essential genes across organisms. Therefore, there is
  clearly a need for a method that is able to predict essential genes across organisms,
  by leveraging network-based features. In this study, we extract several sets of
  network-based features from protein–protein association networks available from
  the STRING database. Our network features include some common measures of centrality,
  and also some novel recursive measures recently proposed in social network literature.
  We extract hundreds of network-based features from networks of 27 diverse organisms
  to predict the essentiality of 87000+ genes. Our results show that network-based
  features are statistically significantly better at classifying essential genes across
  diverse bacterial species, compared to the current state-of-the-art methods, which
  use mostly sequence and a few ‘conventional’ network-based features. Our diverse
  set of network properties gave an AUROC of 0.847 and a precision of 0.320 across
  27 organisms. When we augmented the complete set of network features with sequence-derived
  features, we achieved an improved AUROC of 0.857 and a precision of 0.335. We also
  constructed a reduced set of 100 sequence and network features, which gave a comparable
  performance. Further, we show that our features are useful for predicting essential
  genes in new organisms by using leave-one-species-out validation. Our network features
  capture the local, global and neighbourhood properties of the network and are hence
  effective for prediction of essential genes across diverse organisms, even in the
  absence of other complex biological knowledge. Our approach can be readily exploited
  to predict essentiality for organisms in interactome databases such as the STRING,
  where both network and sequence are readily available. All codes are available at
  https://github.com/RamanLab/nbfpeg.
publication: '*PLOS ONE*'
url_pdf: https://doi.org/10.1371/journal.pone.0208722
doi: 10.1371/journal.pone.0208722
---
