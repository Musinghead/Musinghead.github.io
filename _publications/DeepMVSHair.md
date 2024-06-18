---
title: "DeepMVSHair: Deep Hair Modeling from Sparse Views"
collection: publications
permalink: /publication/DeepMVSHair
excerpt: '**Zhiyi Kuang**, Yiyang Chen, Hongbo Fu, Kun Zhou, Youyi Zheng'
date: 2022-11-30
venue: 'SIGGRAPH Asia 2022 Conference'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3550469.3555385'
citation: ''
---

**Abstract**

We present DeepMVSHair, the first deep learning-based method for multi-view hair strand reconstruction. The key component of our pipeline is HairMVSNet, a differentiable neural architecture which represents a spatial hair structure as a continuous 3D hair growing direction field implicitly. Specifically, given a 3D query point, we decide its occupancy value and direction from observed 2D structure features. With the query point’s pixel-aligned features from each input view, we utilize a view-aware transformer encoder to aggregate anisotropic structure features to an integrated representation, which is decoded to yield 3D occupancy and direction at the query point. HairMVSNet effectively gathers multi-view hair structure features and preserves high-frequency details based on this implicit representation. Guided by HairMVSNet, our hair growing algorithm produces results faithful to input multi-view images. We propose a novel image-guided multi-view strand deformation algorithm to enrich modeling details further. Extensive experiments show that the results by our sparse-view method are comparable to those by state-of-the-art dense multi-view methods and significantly better than those by single-view and sparse-view methods. In addition, our method is an order of magnitude faster than previous multi-view hair modeling methods.