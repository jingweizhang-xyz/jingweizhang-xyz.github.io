---
title: "SAM-Path: A Segment Anything Model for Semantic Segmentation in Digital Pathology"
collection: publications
category: conferences
permalink: /publication/2023-07-SAMPath
excerpt: 'SAM-Path adapts the Segment Anything Model for semantic segmentation in digital pathology by introducing trainable class prompts and incorporating a pathology foundation model encoder.'
date: 2023-07-12
venue: 'MedAGI at International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI) (<strong>Oral</strong>)'
paperurl: https://arxiv.org/abs/2307.09570
citation: '<strong>Jingwei Zhang</strong>, Ke Ma, Saarthak Kapse, Joel Saltz, Maria Vakalopoulou, Prateek Prasanna, Dimitris Samaras, &quot;SAM-Path: A Segment Anything Model for Semantic Segmentation in Digital Pathology&quot;, <i>MedAGI at International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI)</i>, 2023.'
figure: /files/images/publications/2023-07-SAMPath.png
---

**Abstract**. Semantic segmentations of pathological entities have crucial clinical value in computational pathology workflows. Foundation models, such as the Segment Anything Model (SAM), have been recently proposed for universal use in segmentation tasks. SAM shows remarkable promise in instance segmentation on natural images. However, the applicability of SAM to computational pathology tasks is limited due to the following factors: (1) lack of comprehensive pathology datasets used in SAM training and (2) the design of SAM is not inherently optimized for semantic segmentation tasks. In this work, we adapt SAM for semantic segmentation by introducing trainable class prompts, followed by further enhancements through the incorporation of a pathology encoder, specifically a pathology foundation model. Our framework, SAM-Path enhances SAM's ability to conduct semantic segmentation in digital pathology without human input prompts. Through experiments on two public pathology datasets, the BCSS and the CRAG datasets, we demonstrate that the fine-tuning with trainable class prompts outperforms vanilla SAM with manual prompts and post-processing by 27.52% in Dice score and 71.63% in IOU. On these two datasets, the proposed additional pathology foundation model further achieves a relative improvement of 5.07% to 5.12% in Dice score and 4.50% to 8.48% in IOU. 

More information are available at [MICCAI](https://link.springer.com/chapter/10.1007/978-3-031-47401-9_16), [arxiv](https://arxiv.org/abs/2307.09570) and [code](https://github.com/cvlab-stonybrook/SAMPath).  

