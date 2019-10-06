---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## [Ambient VAE: an unsupervised method for image restoration](https://github.com/hamedhaghighi/Ambient-VAE)
* Research on using Varational Auto-encoder as an unsupervised image enhancer.

## [SampleTransformer: modeling high fidelity music in raw audio domain](https://github.com/hamedhaghighi/SampleTransformer)
* Research on capturing long range dependencies of music in audio domain through U-Net like transformer architecture.

## [ITALIC: ITerative and Attentive Lossless Image Compression](https://github.com/hamedhaghighi/UTLC)
* Research on designing fast recursive model for lossless image compression task using attention mechanism.

## [Automatic evaluation of Crown Preparation using Image Processing Technique](https://github.com/hamedhaghighi/CPA-using-Image-processing-techniques)
* Design and implementation of innovative software for crown preparation analysis using QT and OpenCV library.

{% include base_path %}

{% for post in site.projects %}
  {% include archive-single.html %}
{% endfor %}