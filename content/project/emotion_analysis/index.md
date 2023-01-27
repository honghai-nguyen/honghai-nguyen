---
title: Emotion Analysis
summary:  The 2-D Valence and Arousal Space (VA-Space) is the most usual dimensional emotion representation; valence shows how positive or negative an emotional state is, whilst arousal shows how passive or active it is.
    
tags:
  - Computer Vision
date: 2022-04-01
external_link: ''
---
<p align='justify'>
Human emotions recognization contributes to the development of human-computer interaction. The machines understanding human emotions in the real world will significantly contribute to life in the future. This paper introduces the 3rd Affective Behavior Analysis in-the-wild (ABAW3) 2022 challenge. We focused on solving the problem of the Valence-Arousal (VA) estimation and Action Unit (AU) detection. For valence-arousal estimation, we conducted two stages: creating new features from multimodel and temporal learning to predict valence-arousal. First, we make new features; the Gated Recurrent Unit (GRU) and Transformer are combined using a Regular Networks (RegNet) feature, which is extracted from the image. The next step is the GRU combined with local attention to predict valencearousal. The Concordance Correlation Coefficient (CCC) was used to evaluate the model. The result achieved 0.450 for valence and 0.445 for arousal on the test set, outperforming the baseline method with a corresponding CCC of 0.180 for valence and 0.170 for arousal. We also performed additional experiments on the action unit task with simple transformer blocks. We achieved a score of 49.04 on the test set in terms of F1 score, which outperforms the baseline method with a corresponding F1 score of 36.50. Our submission to ABAW3 2022 ranks 3rd for both tasks.

# Feature extraction module: Valence-Arousal Predictor(VAP).

![vap](feature_extraction.png)

# Overview of prediction model: Gated Recurrent Unit combined with local attention.

![va_model](model.png)

# An overview of our action unit detection system.

![au_model](action_units.png)

  </p>
