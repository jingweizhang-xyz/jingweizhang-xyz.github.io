---
title: "Prompt-MIL: Boosting Multi-Instance Learning Schemes via Task-specific Prompt Tuning"
collection: publications
category: conferences
permalink: /publication/2023-03-PromptMIL
excerpt: 'Prompt-MIL integrates prompt tuning into multi-instance learning for end-to-end whole slide image classification, enabling task-specific feature calibration with minimal additional parameters within GPU memory limitation.'
date: 2023-03-21
venue: 'International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI) (<strong>Oral</strong>)'
paperurl: 'https://arxiv.org/abs/2303.12214'
citation: '<strong>Jingwei Zhang</strong>*, Saarthak Kapse*, Ke Ma, Prateek Prasanna, Joel Saltz, Maria Vakalopoulou, Dimitris Samaras, &quot;Prompt-MIL: Boosting Multi-Instance Learning Schemes via Task-specific Prompt Tuning&quot;, <i>International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI)</i>, 2023.'
figure: /files/images/publications/2023-03-PromptMIL.png
---

**Abstract**. Whole slide image (WSI) classification is a critical task in computational pathology, requiring the processing of gigapixel-sized images, which is challenging for current deep-learning methods. Current state of the art methods are based on multi-instance learning schemes (MIL), which usually rely on pretrained features to represent the instances. Due to the lack of task-specific annotated data, these features are either obtained from well-established backbones on natural images, or, more recently from self-supervised models pretrained on histopathology. However, both approaches yield task-agnostic features, resulting in performance loss compared to the appropriate task-related supervision, if available. In this paper, we show that when task-specific annotations are limited, we can inject such supervision into downstream task training, to reduce the gap between fully task-tuned and task agnostic features. We propose Prompt-MIL, an MIL framework that integrates prompts into WSI classification. Prompt-MIL adopts a prompt tuning mechanism, where only a small fraction of parameters calibrates the pretrained features to encode task-specific information, rather than the conventional full fine-tuning approaches. Extensive experiments on three WSI datasets, TCGA-BRCA, TCGA-CRC, and BRIGHT, demonstrate the superiority of Prompt-MIL over conventional MIL methods, achieving a relative improvement of 1.49%-4.03% in accuracy and 0.25%-8.97% in AUROC while using fewer than 0.3% additional parameters. Compared to conventional full fine-tuning approaches, we fine-tune less than 1.3% of the parameters, yet achieve a relative improvement of 1.29%-13.61% in accuracy and 3.22%-27.18% in AUROC and reduce GPU memory consumption by 38%-45% while training 21%-27% faster. 

More information are available at [MICCAI](https://link.springer.com/chapter/10.1007/978-3-031-43993-3_60), [arxiv](https://arxiv.org/abs/2303.12214), [video](https://youtu.be/nLoeoILkh7k) and [code](https://github.com/cvlab-stonybrook/PromptMIL).  


