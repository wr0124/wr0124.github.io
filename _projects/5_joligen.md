---
layout: page
title: Open-Source Contributions to JoliGEN
description: Contributions to an open-source Generative AI framework for image and video generation.
importance: 1
category: work
github: https://github.com/jolibrain/joliGEN
---

## Overview

I contribute to JoliGEN, an open-source Generative AI framework for image and video applications.

My contributions focus mainly on video generation, generative-model experimentation, temporal modeling, inference, evaluation, and improvements to training and testing workflows.

## Selected contributions

### Video generation architecture

Extended generative architectures from image processing to video processing, including:

- support for 5D video tensors
- temporal data loading
- motion modules
- video inference
- training and testing support

[Pull Request #669](https://github.com/jolibrain/joliGEN/pull/669)

### Consistency Models for video generation

Extended Consistency Model functionality to video generation, including conditional inputs and video inference.

[Pull Request #749](https://github.com/jolibrain/joliGEN/pull/749)

### Video evaluation

Improved evaluation of video models so metrics are computed over the complete test dataset rather than only the first test batch.

[Pull Request #854](https://github.com/jolibrain/joliGEN/pull/854)

### Autoregressive video inference

Added an optional fixed temporal initialization noise mode for autoregressive inference, allowing controlled experiments on temporal stability.

[Pull Request #861](https://github.com/jolibrain/joliGEN/pull/861)

### Additional contributions

Other contributions include class-conditioned image/video generation, autoregressive training improvements, evaluation metrics, mask handling, inference tools, debugging, and training utilities.

## Technologies

Python · PyTorch · Generative AI · Diffusion Models · Video Generation · Temporal Modeling · Computer Vision · Git/GitHub
