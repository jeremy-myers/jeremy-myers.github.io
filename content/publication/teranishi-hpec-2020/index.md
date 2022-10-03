---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'SparTen: Leveraging Kokkos for On-node Parallelism in a Second-Order Method
  for Fitting Canonical Polyadic Tensor Models to Poisson Data'
subtitle: ''
summary: ''
authors:
- Keita Teranishi
- Daniel M. Dunlavy
- Jeremy M. Myers
- Richard F. Barrett
tags:
- '"conference"'
- '"refereed"'
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
publishDate: '2020-08-25T23:53:46.577803Z'
publication_types:
- 1
abstract: Canonical Polyadic tensor decomposition using alternate Poisson regression
  (CP-APR) is an effective analysis tool for large sparse count datasets. One of the
  variants using projected damped Newton optimization for row subproblems (PDNR) offers
  quadratic convergence and is amenable to parallelization.  Despite its potential
  effectiveness, PDNR performance on modern high performance computing (HPC) systems
  is not well understood.  To remedy this, we have developed a parallel implementation
  of PDNR using Kokkos, a performance portable parallel programming framework supporting
  efficient runtime of a single code base on  multiple HPC systems. We demonstrate
  that the performance of parallel PDNR can be poor if load imbalance associated with
  the irregular distribution of nonzero entries in the tensor data is not addressed.
  Preliminary results using tensors from the FROSTT data set indicate that using multiple
  kernels to address this imbalance  when solving the PDNR row subproblems in parallel
  can improve performance, with up to 80% speedup on CPUs and 10-fold speedup on NVIDIA
  GPUs.
publication: '*2020 High Performance Extreme Computing Conference (HPEC)*'
---
