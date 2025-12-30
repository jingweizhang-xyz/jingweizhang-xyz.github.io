---
title: "Gigapixel Whole-Slide Images Classification using Locally Supervised Learning"
collection: publications
category: conferences
permalink: /publication/2022-07-PromptMIL
excerpt: 'We propose a locally supervised learning framework that divides a pre-trained network into modules optimized locally with auxiliary models, enabling efficient whole slide image classification without exhaustive patch-level processing.'
date: 2022-07-17
venue: 'International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI) (<strong>Oral</strong>)'
paperurl: 'https://arxiv.org/abs/2207.08267'
citation: '<strong>Jingwei Zhang</strong>*, Xin Zhang*, Ke Ma, Rajarsi Gupta, Joel Saltz, Maria Vakalopoulou, Dimitris Samaras, &quot;Gigapixel Whole-Slide Images Classification using Locally Supervised Learning&quot;, <i>International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI)</i>, 2022.'
figure: /files/images/publications/2023-03-PromptMIL.png
---

**Abstract**. Histopathology whole slide images (WSIs) play a very important role in clinical studies and serve as the gold standard for many cancer diagnoses. However, generating automatic tools for processing WSIs is challenging due to their enormous sizes. Currently, to deal with this issue, conventional methods rely on a multiple instance learning (MIL) strategy to process a WSI at patch level. Although effective, such methods are computationally expensive, because tiling a WSI into patches takes time and does not explore the spatial relations between these tiles. To tackle these limitations, we propose a locally supervised learning framework which processes the entire slide by exploring the entire local and global information that it contains. This framework divides a pre-trained network into several modules and optimizes each module locally using an auxiliary model. We also introduce a random feature reconstruction unit (RFR) to preserve distinguishing features during training and improve the performance of our method by 1% to 3%. Extensive experiments on three publicly available WSI datasets: TCGA-NSCLC, TCGA-RCC and LKS, highlight the superiority of our method on different classification tasks. Our method outperforms the state-of-the-art MIL methods by 2% to 5% in accuracy, while being 7 to 10 times faster. Additionally, when dividing it into eight modules, our method requires as little as 20% of the total gpu memory required by end-to-end training.

More information are available at [MICCAI](https://link.springer.com/chapter/10.1007/978-3-031-16434-7_19), [arxiv](https://arxiv.org/abs/2207.08267), [video](https://youtu.be/_svTenXpjpw) and [code](https://github.com/cvlab-stonybrook/local_learning_wsi).  

