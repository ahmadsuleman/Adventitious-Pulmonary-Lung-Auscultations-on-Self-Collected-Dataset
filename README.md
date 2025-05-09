# Real-Time Detection and Classification of Lung Auscultations on Self Collected Dataset Using Machine Learning

> **Note:** This repository is currently under development and the code will be made publicly available upon the acceptance of the manuscript.

## Overview

Pulmonary diseases, driven largely by respiratory inflammation, account for over 3 million deaths globally each year. Accurate diagnosis remains challenging due to overlapping symptoms across various conditions. This research introduces a novel, real-time diagnostic framework based on lung sound (LS) analysis using a purpose-built **Lung Auscultation Acquisition Setup (LAAS)**.

The study involves a unique dataset collected under real-world hospital conditions from **532 subjects**:
- 200 Healthy individuals  
- 202 with Chronic Obstructive Pulmonary Disease (COPD)  
- 130 with Pneumothorax (PNT)

![Pulmonary Lung Auscultations on Self-Collected Dataset](overview.jpg)

## Highlights

- **Data Collection**: Lung sounds were acquired using LAAS in clinical settings.
- **Feature Extraction**: Performed via wavelet decomposition.
- **Machine Learning Models Used**:
  - Cubic Support Vector Machine (C-SVM)
  - Linear SVM (L-SVM)
  - k-Nearest Neighbors (KNN)
  - Decision Tree (DT)
  - Random Forest (RF)
  - Naive Bayes (NB)
  - XGBoost
  - Logistic Regression (LR)
  - Random Forest with Extra Trees (RF-ET)
  - AdaBoost (AB)

- **Best Performing Model**:  
  - **Cubic-SVM**  
    - Normal: 99.5%  
    - COPD: 99.5%  
    - PNT: 100%

- **Interpretability**: Model decisions explained using **SHAP (Shapley Additive Explanations)**.

## Goals

This repository aims to:
- Share datasets (upon publication)
- Provide complete code for data preprocessing, model training, and evaluation
- Include interpretability scripts for SHAP analysis
- Enable reproducibility of the results

## Current Status

⏳ **Under Review**  
This repository will be updated with the full source code and dataset access upon manuscript acceptance.

## License

This work will be released under an open-source license post-acceptance.

---

Stay tuned! For questions or collaboration opportunities, feel free to reach out.


