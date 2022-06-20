---
title: Improving Generalization of Metric Learning via Listwise Self-distillation
publication_types:
  - "3"
authors:
  - admin
  - Fan Yang
  - Zheng Wang
  - Shin'ichi Satoh
author_notes:
  - First author
abstract: Most deep metric learning (DML) methods employ a strategy that forces
  all positive samples to be close in the embedding space while keeping them
  away from negative ones. However, such a strategy ignores the internal
  relationships of positive (negative) samples and often leads to overfitting,
  especially in the presence of hard samples and mislabeled samples. In this
  work, we propose a simple yet effective regularization, namely Listwise
  Self-Distillation (LSD), which progressively distills a model's own knowledge
  to adaptively assign a more appropriate distance target to each sample pair in
  a batch. LSD encourages smoother embeddings and information mining within
  positive (negative) samples as a way to mitigate overfitting and thus improve
  generalization. Our LSD can be directly integrated into general DML
  frameworks. Extensive experiments show that LSD consistently boosts the
  performance of various metric learning methods on multiple datasets.
draft: false
featured: false
image:
  filename: embedding.jpg
  focal_point: Smart
  preview_only: false
date: 2022-06-20T02:34:39.650Z
---
