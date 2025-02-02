---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Moonshine: An Online Randomness Distiller for Zero-Involvement Authentication'
subtitle: ''
summary: ''
authors:
- Jack West
- Kyuin Lee
- Suman Banerjee
- Younghyun Kim
- George K. Thiruvathukal
- Neil Klingensmith
tags: []
categories: []
date: '2021-01-01'
lastmod: 2022-11-19T22:39:23-06:00
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
publishDate: '2023-07-11T04:48:53.623141Z'
publication_types:
- '1'
abstract: Context-based authentication is a method for transparently validating another
  device's legitimacy to join a network based on location. Devices can pair with one
  another by continuously harvesting environmental noise to generate a random key
  with no user involvement. However, there are gaps in our understanding of the theoretical
  limitations of environmental noise harvesting, making it difficult for researchers
  to build efficient algorithms for sampling environmental noise and distilling keys
  from that noise. This work explores the information-theoretic capacity of context-based
  authentication mechanisms to generate random bit strings from environmental noise
  sources with known properties. Using only mild assumptions about the source process's
  characteristics, we demonstrate that commonly-used bit extraction algorithms extract
  only about 10% of the available randomness from a source noise process. We present
  an efficient algorithm to improve the quality of keys generated by context-based
  methods and evaluate it on real key extraction hardware. Moonshine is a randomness
  distiller which is more efficient at extracting bits from an environmental entropy
  source than existing methods. Our techniques nearly double the quality of keys as
  measured by the NIST test suite, producing keys that can be used in real-world authentication
  scenarios.
publication: '*Information Processing in Sensor Networks 2021 (IPSN 2021)*'
doi: TBD
links:
- name: URL
  url: https://ecommons.luc.edu/cs_facpubs/270/
---
