---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Using Computation Effectively for Scalable Poisson Tensor Factorization: Comparing Methods Beyond Computational Efficiency'
subtitle: ''
summary: ''
authors:
- Jeremy M. Myers
- Daniel M. Dunlavy
tags: []
categories: []
date: '2021-09-22'
lastmod: 2022-06-30T11:49:46-07:00
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
publishDate: '2021-09-22T11:49:46.443967Z'
publication_types:
- 1
abstract: 'Poisson Tensor Factorization (PTF) is an important data analysis method for analyzing patterns and relationships in multiway count data. In this work, we consider several algorithms for computing a low-rank PTF of tensors with sparse count data values via maximum likelihood estimation. Such an approach reduces to solving a nonlinear, non-convex optimization problem, which can leverage considerable parallel computation due to the structure of the problem. However, since the maximum likelihood estimator corresponds to the global minimizer of this optimization problem, it is important to consider how effective methods are at both leveraging this inherent parallelism as well as computing a good approximation to the global minimizer. In this work we present comparisons of multiple methods for PTF that illustrate the tradeoffs in computational efficiency and accurately computing the maximum likelihood estimator. We present results using synthetic and real-world data tensors to demonstrate some of the challenges when choosing a method for a given tensor.'
publication: '*2021 High Performance Extreme Computing Conference (HPEC)*'
---
