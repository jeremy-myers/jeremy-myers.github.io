---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Parameter Sensitivity Analysis of the SparTen High Performance Sparse Tensor
  Decomposition Software
subtitle: ''
summary: ''
authors:
- Jeremy M. Myers
- Daniel M. Dunlavy
- Keita Teranishi
- D. S. Hollman
tags: []
categories: []
date: '2020-09-01'
lastmod: 2020-08-25T17:53:46-06:00
featured: true
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
publishDate: '2020-08-25T23:53:46.443967Z'
publication_types:
- 1
abstract: 'Tensor decomposition models play an increasingly important role in modern
  data science applications. One problem of particular interest is fitting a  low-rank
  Canonical Polyadic (CP) tensor decomposition model when the tensor has sparse structure
  and the tensor elements are nonnegative count data. SparTen is a high-performance
  C++ library which computes a low-rank decomposition using different solvers: a first-order
  quasi-Newton or a second-order damped Newton method, along with the appropriate
  choice of runtime parameters. Since default parameters in SparTen are tuned to experimental
  results in prior published work on a single real-world dataset conducted using MATLAB
  implementations of these methods, it remains unclear if the parameter defaults in
  SparTen are appropriate for general tensor data. Furthermore, it is unknown how
  sensitive algorithm convergence is to changes in the input parameter values. This
  report addresses these unresolved issues with large-scale experimentation on three
  benchmark tensor data sets. Experiments were conducted on several different CPU
  architectures and replicated with many initial states to establish generalized profiles
  of algorithm convergence behavior.'
publication: '*2020 High Performance Extreme Computing Conference (HPEC)*'
---
