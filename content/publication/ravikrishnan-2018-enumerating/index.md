---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Enumerating all possible biosynthetic pathways in metabolic networks.
subtitle: ''
summary: ''
authors:
- Aarthi Ravikrishnan
- Meghana Nasre
- Karthik Raman
tags:
- '"communities metabolic-networks myown pathfinding"'
categories: []
date: '2018-07-01'
lastmod: 2020-10-31T20:24:43+05:30
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
publishDate: '2020-10-31T15:04:36.452801Z'
publication_types:
- '2'
abstract: Exhaustive identification of all possible alternate pathways that exist
  in metabolic networks can provide valuable insights into cellular metabolism. With
  the growing number of metabolic reconstructions, there is a need for an efficient
  method to enumerate pathways, which can also scale well to large metabolic networks,
  such as those corresponding to microbial communities. We developed MetQuest, an
  efficient graph-theoretic algorithm to enumerate all possible pathways of a particular
  size between a given set of source and target molecules. Our algorithm employs a
  guided breadth-first search to identify all feasible reactions based on the availability
  of the precursor molecules, followed by a novel dynamic-programming based enumeration,
  which assembles these reactions into pathways of a specified size producing the
  target from the source. We demonstrate several interesting applications of our algorithm,
  ranging from identifying amino acid biosynthesis pathways to identifying the most
  diverse pathways involved in degradation of complex molecules. We also illustrate
  the scalability of our algorithm, by studying large graphs such as those corresponding
  to microbial communities, and identify several metabolic interactions happening
  therein. MetQuest is available as a Python package, and the source codes can be
  found at https://github.com/RamanLab/metquest .
publication: '*Scientific reports*'
url_pdf: http://view.ncbi.nlm.nih.gov/pubmed/29967471
---
