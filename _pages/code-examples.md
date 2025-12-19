---
title: ""
permalink: /code-examples/
layout: archive
author_profile: true
---
## Python Codes
### BERT Training Pipeline 
A training pipeline for **[binary text classification using BERT / BioBERT / ClinicalBERT](https://github.com/elle-y-wang/Code-Examples/tree/main/Python_Codes/Bert_Training)**:
- 5-fold stratified cross-validation + early stopping (AUPRC primary)
- Class-weighted loss for imbalance
- AMP support when CUDA is available
- Safetensors-first loading and CVE-aware fallback behavior
- Out-of-fold predictions and fold ensemble inference

🔗 **[View code on GitHub](https://github.com/elle-y-wang/Code-Examples/blob/071e0b6bafbbdb76c0dc55956217b349345310b2/Python_Codes/Bert_Training/bert_training_en.ipynb)**  


## R Codes
### K-means Clustering Analysis

A reusable **[clustering analysis workflow](https://github.com/elle-y-wang/Code-Examples/blob/071e0b6bafbbdb76c0dc55956217b349345310b2/R_Codes/Clustering_Analysis/ReadMe.md)** for numeric feature matrices:
- Standardization 
- K selection: WSS (elbow), Pseudo-F, Silhouette, Gap statistic
- Final k-means fit + exported cluster labels + optional cluster summaries

🔗 **[View code on GitHub](https://github.com/elle-y-wang/Code-Examples/blob/071e0b6bafbbdb76c0dc55956217b349345310b2/R_Codes/Clustering_Analysis/kmeans_clustering.R)**  

### SMD-based Meta-analysis and Visualization

**[Standardized mean difference (SMD)–based meta-analysis pipeline](https://github.com/elle-y-wang/Code-Examples/blob/071e0b6bafbbdb76c0dc55956217b349345310b2/R_Codes/Meta-analysis/ReadMe.md)**
with publication-quality visualizations.

- Effect size calculation using `metafor`
- Fixed- and random-effects models
- Sensitivity and influence diagnostics
- Forest plots generated with `forestploter`

🔗 **[View code on GitHub](https://github.com/elle-y-wang/Code-Examples/blob/071e0b6bafbbdb76c0dc55956217b349345310b2/R_Codes/Meta-analysis/SMD_Meta.r)**


