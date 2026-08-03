---
title: "Intersectional fairness in vision-language models for medical image disease classification"
collection: publications
permalink: /publication/2026-08-03-intersectional-fairness-vlm
redirect_from:
  - /publication/2025-12-01-intersectional-fairness-vlm
excerpt: 'Cross-Modal Alignment Consistency (CMAC-MMD), a training framework that standardises diagnostic certainty across intersectional patient subgroups without requiring sensitive demographic data at inference, reducing missed-diagnosis gaps while improving AUC on dermatology and glaucoma cohorts.'
date: 2026-08-03
venue: 'npj Digital Medicine'
paperurl: 'https://www.nature.com/articles/s41746-026-03030-5'
citation: 'Yupeng Zhang, Adam G. Dunn, Usman Naseem, Jinman Kim. (2026). &quot;Intersectional fairness in vision-language models for medical image disease classification.&quot; <i>npj Digital Medicine</i>. doi:10.1038/s41746-026-03030-5'
---

Medical AI systems, particularly multimodal vision–language models, often exhibit intersectional biases, being systematically less confident when diagnosing marginalised patient subgroups and producing higher rates of missed diagnoses. This work introduces Cross-Modal Alignment Consistency (CMAC-MMD), a training framework that standardises diagnostic certainty across intersectional patient subgroups without requiring sensitive demographic data during clinical inference.

The approach was evaluated on 10,015 skin lesion images (HAM10000) with external validation on 12,000 images (BCN20000), and on 10,000 fundus images for glaucoma detection (Harvard-FairVLMed), stratifying performance by intersectional age, gender, and race attributes. In the dermatology cohort, the method reduced the overall intersectional missed-diagnosis gap (ΔTPR) from 0.50 to 0.26 while improving AUC from 0.94 to 0.97 compared with standard training. For glaucoma screening, it reduced ΔTPR from 0.41 to 0.31, achieving a better AUC of 0.72 (vs. 0.71 baseline).

[Read the paper in npj Digital Medicine](https://www.nature.com/articles/s41746-026-03030-5)
