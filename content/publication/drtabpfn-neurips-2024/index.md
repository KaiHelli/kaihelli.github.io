---
title: 'Drift-Resilient TabPFN: In-Context Learning Distribution Shifts on Tabular
  Data'
authors:
- Kai Helli
- David Schnurr
- Noah Hollmann
- Samuel Müller
- Frank Hutter
date: '2024-11-06'
publishDate: '2024-11-06T19:27:43.401886Z'
publication_types:
- paper-conference
publication: '*The Thirty-eighth Annual Conference on Neural Information Processing
  Systems*'
abstract: "While most ML models expect independent and identically distributed data,
  this assumption is often violated in real-world scenarios due to distribution shifts,
  resulting in the degradation of machine learning model performance. Until now, no
  tabular method has consistently outperformed classical supervised learning, which
  ignores these shifts. To address temporal distribution shifts, we present Drift-Resilient
  TabPFN, a fresh approach based on In-Context Learning with a Prior-Data Fitted Network
  that learns the learning algorithm itself: it accepts the entire training dataset
  as input and makes predictions on the test set in a single forward pass. Specifically,
  it learns to approximate Bayesian inference on synthetic datasets drawn from a prior
  that specifies the model's inductive bias. This prior is based on structural causal
  models (SCM), which gradually shift over time. To model shifts of these causal models,
  we use a secondary SCM, that specifies changes in the primary model parameters.
  The resulting Drift-Resilient TabPFN can be applied to unseen data, runs in seconds
  on small to moderately-sized datasets and needs no hyperparameter tuning. Comprehensive
  evaluations across 18 synthetic and real-world datasets demonstrate large performance
  improvements over a wide range of baselines, such as XGB, CatBoost, TabPFN, and
  applicable methods featured in the Wild-Time benchmark. Compared to the strongest
  baselines, it improves accuracy from 0.688 to 0.744 and ROC AUC from 0.786 to 0.832
  while maintaining stronger calibration. This approach could serve as significant
  groundwork for further research on out-of-distribution prediction."
links:
- name: URL
  url: https://openreview.net/forum?id=p3tSEFMwpG
  url_pdf: https://openreview.net/pdf?id=p3tSEFMwpG
  featured: true
---
