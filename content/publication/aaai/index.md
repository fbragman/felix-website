---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Temporal Cluster Assignment for Efficient Real-Time Video Segmentation"
subtitle: "Token clustering for efficient video models"
summary: "Vision Transformers, especially Swin, are strong backbones for video segmentation but remain computationally heavy, limiting real-time use. Conventional token pruning struggles with Swin’s fixed window scheme, while existing clustering methods ignore temporal redundancy. To address this, the proposed Temporal Cluster Assignment (TCA) leverages temporal coherence to refine token clusters without fine-tuning, improving efficiency and accuracy across multiple video benchmarks, including surgical data."
authors:
- Ka-Wai Yung
- Felix Bragman
- Jialang Xu
- Imanol Luengo
- Danail Stoyanov
- Evangelos B. Mazomenos
author_notes:
- "Equal contributions"
- "Equal contributions"
- "Equal contributions"
tags: [efficient ML, token clustering]
categories: []
date: 2025-08-07
featured: false
abstract: "Vision Transformers have substantially advanced the capabilities of segmentation models across both image and video domains. Among them, the Swin Transformer stands out for its ability to capture hierarchical, multi-scale representations, making it a popular backbone for segmentation in videos. However, despite its window-attention scheme, it still incurs a high computational cost, especially in larger variants commonly used for dense prediction in videos. This remains a major bottleneck for real-time, resource-constrained applications. Whilst token reduction methods have been proposed to alleviate this, the window-based attention mechanism of Swin requires a fixed number of tokens per window, limiting the applicability of conventional pruning techniques. Meanwhile, training-free token clustering approaches have shown promise in image segmentation while maintaining window consistency. Nevertheless, they fail to exploit temporal redundancy, missing a key opportunity to further optimize video segmentation performance. We introduce Temporal Cluster Assignment (TCA), a lightweight and effective, fine-tuning-free strategy that enhances token clustering by leveraging temporal coherence across frames. Instead of indiscriminately dropping redundant tokens, TCA refines token clusters using temporal correlations, thereby retaining fine-grained details while significantly reducing computation. Extensive evaluations on YouTube-VIS 2019, YouTube-VIS 2021, OVIS, and a private surgical video dataset show that TCA consistently boosts the accuracy-speed trade-off of existing clustering-based methods. Our results demonstrate that TCA generalizes competently across both natural and domain-specific videos."
publication: "in submission"
url_pdf: "https://arxiv.org/abs/2508.05851"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Temporal cluster assignment"
  preview_only: false
  focal_pont: "Center"
  placement: 1

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
