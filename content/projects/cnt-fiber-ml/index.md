---
title: Machine Learning for Carbon Nanotube Fiber Characterization
date: 2024-11-15
tags:
  - Machine Learning
  - Materials Science
  - Experimental Mechanics
  - Data Pipeline
links:
  - icon: brands/github
    name: View on GitHub
    url: https://github.com/AshyScripts/CNT_Yarns_ML_Analysis.git
---

Building intelligent experimental workflows for CNT fiber optimization by integrating comprehensive materials characterization with machine learning. Developed automated data pipelines and applied ML techniques to extract insights from 500+ experimental samples.

<!--more-->

## Overview

My PhD research focuses on understanding and optimizing carbon nanotube fiber assemblies through the combination of hands-on experimental mechanics and computational methods. I've built the complete infrastructure for data-driven materials discovery - from lab work to automated analysis pipelines.

## Experimental Foundation

Conducted extensive characterization campaign:
- **SEM Imaging**: 50+ samples, ~500 high-resolution images with quantitative dimensional analysis
- **Mechanical Testing**: Quasi-static tensile tests and DMA across diverse processing conditions
- **Raman Spectroscopy**: Structural characterization and feature extraction
- **Processing**: Laser shockwave compaction and electrical fusion parameter exploration

## Data Infrastructure & ML Analysis

Built end-to-end automated Python pipeline:
- Data collection and registry management across 500+ samples with robust filtering
- Integration of processing parameters with mechanical properties and morphological measurements
- Feature engineering from multi-modal characterization data (SEM dimensions, Raman features, test conditions)
- MLflow implementation for experiment tracking and hyperparameter tuning

## Machine Learning Insights

Applied supervised and unsupervised learning to uncover structure-property relationships:
- Model comparison (Linear Regression, Random Forest, XGBoost, etc.) with RMSE evaluation
- Feature importance analysis identifying key processing parameters
- LOOCV and data-efficient strategies for small dataset challenges
- Cosine similarity analysis of Raman spectral features

## Next Phase

Currently implementing Bayesian optimization with Gaussian Process surrogate models and acquisition functions (EI, UCB) to guide experimental design for the next set of laser-fused CNT fiber samples. This will enable intelligent exploration of the processing parameter space.

## Impact

This work demonstrates the reality of ML in materials science: dealing with scarce, valuable, noisy experimental data where every sample represents hours of lab work. The approach prioritizes extracting maximum insight from existing data while building tools for smarter future experiments.