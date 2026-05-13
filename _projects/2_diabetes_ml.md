---
layout: page
title: Using Machine Learning to Predict Early Diabetes Complications
description: Leveraging ML algorithms to forecast diabetes complications using Canadian primary care data
img: assets/img/diabetes_ml.png
importance: 2
category: Academic Research
related_publications: false
---

**Institute**: University of Toronto
**Project Status**: Ongoing

## Overview

This project aims to predict early diabetes complications using machine learning techniques. By analyzing data from the Canadian Primary Care Sentinel Surveillance Network (CPCSSN), we develop predictive models to identify patients at high risk of developing complications such as cardiovascular disease, retinopathy, and nephropathy.

## Research Questions

- Can machine learning models effectively predict diabetes complications earlier than traditional methods?
- Which patient features are most predictive of specific complications?
- How do different ML algorithms compare in terms of predictive performance and clinical utility?

## Data Source

**Canadian Primary Care Sentinel Surveillance Network (CPCSSN)**: A pan-Canadian network of primary care practices that collects standardized electronic medical record data. The dataset includes:
- Patient demographics
- Clinical measurements (HbA1c, blood pressure, BMI)
- Laboratory results
- Medication history
- Diagnosis codes

## Machine Learning Models

We evaluated five different algorithms:
- **Logistic Regression**: Baseline linear model for binary classification
- **Random Forest**: Ensemble method combining multiple decision trees
- **XGBoost**: Gradient boosting framework with superior performance
- **Deep Neural Network**: Multi-layer neural network for complex pattern recognition
- **Support Vector Machine (SVM)**: Kernel-based classification algorithm

## Core Features

- **Feature Engineering**: Extracted temporal patterns and created composite risk indicators
- **Model Comparison**: Systematic evaluation across multiple performance metrics
- **Interpretability Analysis**: SHAP values to understand feature importance
- **Clinical Validation**: Results validated against clinical guidelines

## Results

- **XGBoost** demonstrated the best overall performance with highest AUC-ROC scores
- Identified key predictive features: HbA1c levels, duration of diabetes, and comorbidity burden
- Achieved early detection of complications 6-12 months before clinical diagnosis
- Model interpretability revealed actionable risk factors for clinical intervention

## Significance

### Clinical Practice
- Enables proactive identification of high-risk patients
- Supports personalized treatment planning and resource allocation
- Provides decision support tools for primary care physicians

### Research Contribution
- Demonstrates effectiveness of ML in diabetes complication prediction
- Establishes benchmark for future studies using CPCSSN data
- Contributes to precision medicine approaches in chronic disease management

## Links

- **GitHub**: [Repository Link](https://github.com/liuxiny9/diabetes-ml-prediction)
