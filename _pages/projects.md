---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
## [Contrastive Learning-based Framework for Sim-to-Real Mapping of Lidar Point Clouds in Autonomous Driving Systems](https://arxiv.org/abs/2312.15817)
* Research on utilising an unpaired image-to-image translation framework for sim-to-real mapping of Lidar point clouds.

## [Accelerating Stereo Image Simulation for Automotive Applications Using Neural Stereo Super Resolution](https://ieeexplore.ieee.org/document/10173712)
* Proposing a tranformer-based stereo super resolution network to speed up stereo image rendering.

## [Ambient VAE: an Unsupervised Method for Image Restoration](https://github.com/hamedhaghighi/Ambient-VAE)
* Research on using varational auto-encoders for the unsupervised image restoration task.

## [SampleTransformer: Modelling High Fidelity Music in Raw Audio Domain](https://github.com/hamedhaghighi/SampleTransformer)
* Research on capturing long range dependencies of music in audio domain through U-Net like transformer architecture.

## [ITALIC: ITerative and Attentive Lossless Image Compression](https://github.com/hamedhaghighi/UTLC)
* Research on designing fast recursive model for lossless image compression task using attention mechanism.

## [Automatic evaluation of Crown Preparation using Image Processing Technique](https://github.com/hamedhaghighi/CPA-using-Image-processing-techniques)
* Design and implementation of innovative software for evaluating crown(tooth) preparation.

{% include base_path %}

{% for post in site.projects %}
  {% include archive-single.html %}
{% endfor %}
