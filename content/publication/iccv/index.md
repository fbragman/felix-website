---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Stochastic Filter Groups for Multi-Task CNNs - Learning Specialist and Generalist Convolution Kernels"
subtitle: "Learning multi-task architectures with variational inference"
summary: "In this paper, we present a probabilistic approach to learning task-specific and shared representations in CNNs for multi-task learning. We propose stochastic filter groups (SFG), a mechanism to assign convolution kernels in each layer to specialist or generalist groups, which are specific to or shared across different tasks, respectively. The SFG modules determine the connectivity between layers and the structures of task-specific and shared representations in the network. We employ variational inference to learn the posterior distribution over the possible grouping of kernels and network parameters."
authors: [Felix Bragman*, Ryutaro Tanno*, Sebastien Ourselin, Daniel C. Alexander and M. Jorge Cardoso]
tags: [multi-task learning, representation learning, variational inference, filter groups]
categories: []
date: 2019-10-28
featured: true
abstract: "The performance of multi-task learning in Convolutional Neural Networks (CNNs) hinges on the design of feature sharing between tasks within the architecture. The number of possible sharing patterns are combinatorial in the depth of the network and the number of tasks, and thus hand-crafting an architecture, purely based on the human intuitions of task relationships can be time-consuming and suboptimal.\n 

In this paper, we present a probabilistic approach to learning task-specific and shared representations in CNNs for multi-task learning. Specifically, we propose stochastic filter groups (SFG), a mechanism to assign convolution kernels in each layer to specialist or generalist groups, which are specific to or shared across different tasks, respectively.\n 

The SFG modules determine the connectivity between layers and the structures of task-specific and shared representations in the network. We employ variational inference to learn the posterior distribution over the possible grouping of kernels and network parameters. Experiments demonstrate that the proposed method generalises across multiple tasks and shows improved performance over baseline methods."
publication: "**ICCV (oral, top 4%)**"
url_code: "https://github.com/fbragman/NiftyNet/tree/multitask_group"
url_video: "https://www.youtube.com/watch?v=9Sx2qWKGzlc&feature=youtu.be&t=3726"
url_pdf: "https://arxiv.org/abs/1908.09597"
url_poster: "files/iccv_poster.pdf"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Probabilistic sampling of feature groups"
  preview_only: false
  focal_pont: "smart"

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
