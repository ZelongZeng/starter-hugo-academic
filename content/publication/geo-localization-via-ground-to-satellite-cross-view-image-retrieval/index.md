---
title: "Geo-Localization via Ground-to-Satellite Cross-View Image Retrieval "
publication_types:
  - "2"
authors:
  - admin
  - Zheng Wang
  - Fan Yang
  - Shin'ichi Satoh
author_notes:
  - First author
doi: 10.1109/TMM.2022.3144066
publication: In *IEEE Transactions on Multimedia*
publication_short: In *TMM*
abstract: >-
  The large variation of viewpoint and irrelevant content around the target
  always hinder accurate image retrieval and its subsequent tasks. In this
  paper, we investigate an extremely challenging task: given a ground-view image
  of a landmark, we aim to achieve cross-view geo-localization by searching out
  its corresponding satellite-view images. Specifically, the challenge comes
  from the gap between ground-view and satellite-view, which includes not only
  large viewpoint changes (some parts of the landmark may be invisible from
  front view to top view) but also highly irrelevant background (the target
  landmark tend to be hidden in other surrounding buildings), making it
  difficult to learn a common representation or a suitable mapping.


  To address this issue, we take advantage of drone-view information as a bridge between ground-view and satellite-view domains. We propose a Peer Learning and Cross Diffusion (PLCD) framework. PLCD consists of three parts: 1) a peer learning across ground-view and drone-view to find visible parts to benefit ground-drone cross-view representation learning; 2) a patch-based network for satellite-drone cross-view representation learning; 3) a cross diffusion between ground-drone space and satellite-drone space. Extensive experiments conducted on the University-Earth and University-Google datasets show that our method outperforms state-of-the-arts significantly.
draft: false
featured: false
tags:
  - Image Retrieval
categories:
  - Journal
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
date: 2022-01-16T11:02:13.743Z
---
{{% callout note %}}
Click the *PDF, Cite or DOI* buttons above to get the relative file or metadata. 
{{% /callout %}}