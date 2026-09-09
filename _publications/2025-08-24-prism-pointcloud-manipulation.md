---
title: "PRISM: Pointcloud Reintegrated Inference via Segmentation and Cross-attention for Manipulation"
collection: publications
permalink: /publication/2025-08-24-prism-pointcloud-manipulation
excerpt: 'An end-to-end imitation learning framework that learns directly from raw point cloud observations and robot states, combining object-level segmentation with cross-attention to handle cluttered, contact-rich manipulation tasks.'
date: 2025-08-24
venue: 'IEEE Robotics and Automation Letters (RA-L)'
paperurl: 'https://arxiv.org/abs/2507.04633'
citation: 'D. Huang, Z. Cai, Y. Hao, Z. Li, C. Chew. &quot;PRISM: Pointcloud Reintegrated Inference via Segmentation and Cross-attention for Manipulation.&quot; IEEE Robotics and Automation Letters, 2025.'
---

PRISM is an end-to-end framework for robust imitation learning in robot manipulation. Rather than relying on pre-trained models or external datasets, PRISM learns directly from raw point cloud observations and robot proprioceptive states. The framework comprises three components: a segmentation embedding unit that partitions the raw point cloud into distinct object clusters and encodes local geometric detail, a cross-attention module that fuses these visual features with robot joint states to highlight task-relevant targets, and a diffusion module that translates the fused representation into smooth robot actions. PRISM is designed to remain robust in cluttered, object-dense scenes where fixed-camera-view and keyframe-based 3D methods tend to struggle.

**Links:** [arXiv preprint](https://arxiv.org/abs/2507.04633) &middot; [IEEE Xplore](https://ieeexplore.ieee.org/document/11150701/) &middot; [Code](https://github.com/czknuaa/PRISM)

Recommended citation: D. Huang, Z. Cai, Y. Hao, Z. Li, C. Chew (2025). "PRISM: Pointcloud Reintegrated Inference via Segmentation and Cross-attention for Manipulation." <i>IEEE Robotics and Automation Letters</i>.
