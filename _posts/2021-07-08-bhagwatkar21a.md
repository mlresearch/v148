---
title: Paying Attention to Video Generation
abstract: Video generation is a challenging research topic which has been tackled
  by a variety of methods including Generative Adversarial Networks (GANs), Variational
  Autoencoders (VAE), optical flow and autoregressive models. However, most of the
  existing works model the task as image manipulation and learn pixel-level transforms.
  In contrast, we propose a latent vector manipulation approach using sequential models,
  particularly the Generative Pre-trained Transformer (GPT). Further, we propose a
  novel Attention-based Discretized Autoencoder (ADAE) which learns a finite-sized
  codebook that serves as a basis for latent space representations of frames, to be
  modelled by the sequential model. To tackle the reduced resolution or the diversity
  bottleneck caused by the finite codebook, we propose attention-based soft-alignment
  instead of a hard distance-based choice for sampling the latent vectors. We extensively
  evaluate the proposed approach on the BAIR Robot Pushing, Sky Time-lapse and Dinosaur
  Game datasets and compare with state-of-the-art (SOTA) approaches. Upon experimentation,
  we find that our model suffers mode collapse owing to a single vector latent space
  learned by the ADAE. The cause for this mode collapse is traced back to the peaky
  attention scores resulting from the codebook (Keys and Values) and the encoder’s
  output (Query). Through our findings, we highlight the importance of reliable latent
  space frame representations for successful sequential modelling.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bhagwatkar21a
month: 0
tex_title: Paying Attention to Video Generation
firstpage: 139
lastpage: 154
page: 139-154
order: 139
cycles: false
bibtex_author: Bhagwatkar, Rishika and Fitter, Khurshed and Bachu, Saketh and Kulkarni,
  Akshay and Chiddarwar, Shital
author:
- given: Rishika
  family: Bhagwatkar
- given: Khurshed
  family: Fitter
- given: Saketh
  family: Bachu
- given: Akshay
  family: Kulkarni
- given: Shital
  family: Chiddarwar
date: 2021-07-08
address:
container-title: NeurIPS 2020 Workshop on Pre-registration in Machine Learning
volume: '148'
genre: inproceedings
issued:
  date-parts:
  - 2021
  - 7
  - 8
pdf: http://proceedings.mlr.press/v148/bhagwatkar21a/bhagwatkar21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
