---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Uncertainty in multitask learning: joint representations for probabilistic MR-only radiotherapy planning"
subtitle: "Approximately Bayesian multi-task learning"
summary: "We propose a probabilistic multi-task network that estimates: 1) intrinsic uncertainty through a heteroscedastic noise model for spatially-adaptive task loss weighting and 2) parameter uncertainty through approximate Bayesian inference. This allows sampling of multiple segmentations and synCTs that share their network representation."
authors: [Felix Bragman, Ryutaro Tanno, Zach Eaton-Rosen, Wenqi Li, David J. Hawkes, Sebastien Ourselin, Daniel C. Alexander, Jamie McClelland, M. Jorge Cardoso]
tags: []
categories: []
date: 2018-09-01T20:59:44+01:00
featured: true
abstract: "Multi-task neural network architectures provide a mechanism that jointly integrates information from distinct sources. It is ideal in the context of MR-only radiotherapy planning as it can jointly regress a synthetic CT (synCT) scan and segment organs-at-risk (OAR) from MRI. \n

We propose a probabilistic multi-task network that estimates: 1) intrinsic uncertainty through a heteroscedastic noise model for spatially-adaptive task loss weighting and 2) parameter uncertainty through approximate Bayesian inference. This allows sampling of multiple segmentations and synCTs that share their network representation. \n

We test our model on prostate cancer scans and show that it produces more accurate and consistent synCTs with a better estimation in the variance of the errors, state of the art results in OAR segmentation and a methodology for quality assurance in radiotherapy treatment planning. "
publication: "**MICCAI (spotlight oral, top 4%)**"
url_pdf: "https://arxiv.org/abs/1806.06595"
url_poster: "files/miccai_poster.pdf"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "smart"
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: [multi-task]
---
