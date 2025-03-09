# TTE-v2: Target Trial Emulation with K-Means Clustering
### Overview
This repository contains the implementation of TTE-v2, an enhanced version of Target Trial Emulation (TTE) that integrates K-Means clustering to improve causal effect estimation in observational data studies. TTE-v2 builds on the standard TTE framework by incorporating clustering to account for patient heterogeneity, enabling subgroup-specific analyses and more precise treatment effect estimates. The project is implemented in Python and includes a Jupyter Notebook for step-by-step execution and analysis.

### What is TTE-v2?
Target Trial Emulation (TTE) is a statistical framework that emulates randomized controlled trials using observational data, addressing biases such as confounding and informative censoring. TTE-v2 extends this by integrating K-Means clustering to segment patients into subgroups based on baseline characteristics (e.g., age, x2, x4). This allows for cluster-specific modeling, improved covariate adjustment, and detailed subgroup analyses, enhancing the robustness and interpretability of causal effect estimates in longitudinal studies.

### Why K-Means Clustering?
Improved Adjustment for Confounding: Clustering identifies patient subgroups with similar profiles, enabling more precise covariate adjustment in weight and outcome models.
Heterogeneity Detection: Uncovers latent subgroups with differential treatment responses, improving the granularity of causal inferences.
Efficiency: Cluster-specific models reduce computational complexity compared to a single global model, especially for large datasets.
Enhanced Interpretability: Provides visual and statistical insights into treatment effect variations across patient subgroups.
