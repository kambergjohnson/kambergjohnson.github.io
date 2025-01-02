---
layout: project
type: project
image: images/resistance-prediction-project-small.png
title: "Predicting resistance to small molecule kinase inhibitors"
date: 2024
published: true
labels:
  - drug resistance
  - computational prediction
  - EGFR
summary: "We report on a physics-based computationally driven lead identification approach that identified structurally unique imidazo pyrazoles as reversible and wild-type-sparing EGFR TKIs of classical mutations."
---

Drug resistance is a critical challenge in treating diseases like cancer and infectious disease. This study presents a novel computational workflow for predicting on-target resistance mutations to small molecule inhibitors (SMIs). The approach integrates genetic models with alchemical free energy perturbation (FEP+) calculations to identify likely resistance mutations. Specifically, a genetic model, RECODE, leverages cancer-specific mutation patterns to prioritize probable amino acid changes. Physics-based calculations assess the impact of these mutations on protein stability, endogenous substrate binding, and inhibitor binding. We apply this approach retrospectively to gefitinib and osimertinib, two clinical epidermal growth factor receptor (EGFR) inhibitors used to treat non-small cell lung cancer (NSCLC). Among hundreds of possible mutations, the pipeline accurately predicted 4 out of 11 and 7 out of 19 known binding site mutations for gefitinib and osimertinib, respectively, including the clinically relevant T790M and C797S resistance mutations. This study demonstrates the potential of integrating genetic models and physics-based calculations to predict SMI resistance mutations. This approach can be applied to other kinases and target classes, potentially enabling the design of next-generation inhibitors with improved durability of response in patients.

{% include captioned-image.html image="resistance-prediction-project.png" caption="" %}
