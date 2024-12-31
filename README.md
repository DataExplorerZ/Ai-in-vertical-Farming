# AI-Powered Vertical Farming: Predictive Modeling for Door Status

This repository contains a project that leverages **machine learning** techniques to predict the **door status** (open/closed) in vertical farming cubes based on environmental conditions such as temperature and humidity. The aim is to optimize energy efficiency and crop growth in controlled environments.

---

## Project Overview

Vertical farming offers a sustainable solution for modern agriculture by enabling precise control over environmental conditions. This project uses a dataset of environmental parameters and implements machine learning models to automate door operations, enhancing operational efficiency.

**Key Highlights**:
- Models implemented: **Random Forest**, **Support Vector Machine (SVM)**, and **XGBoost**.
- Dataset preprocessing includes **KNN** and **MICE** imputation techniques.
- Comparative analysis of model performance with metrics like accuracy, precision, recall, and F1-score.

**Top Performing Model**:  
Support Vector Machine (SVM) with an accuracy of **99.36%**.

---

## Files in the Repository

- **`document_classification.ipynb`**:  
  A Jupyter Notebook containing the full workflow:
  - Data preprocessing and feature engineering.
  - Model training and evaluation.
  - Comparative analysis of the algorithms.

- **`vertical_farming_report.pdf`**:  
  A detailed report explaining the project methodology, results, and recommendations.

---

## Dataset

The dataset consists of 400,000 records from vertical farming cubes, including features like:
- Temperature (Layer A and Layer B).
- Humidity (Layer A and Layer B).
- Door status (open/closed).

The data was sourced from [Kaggle](https://www.kaggle.com/) and preprocessed to ensure completeness and reliability.

---

## Results

| **Metric**          | **Random Forest** | **SVM** | **XGBoost** |
|----------------------|-------------------|---------|-------------|
| **Accuracy**         | 99.20%           | 99.36%  | 99.23%      |
| **Precision**        | 99.12%           | 99.37%  | 99.24%      |
| **Recall**           | 99.27%           | 99.34%  | 99.21%      |
| **F1-Score**         | 99.20%           | 99.35%  | 99.23%      |

**Key Insight**:  
SVM emerged as the best-performing model, demonstrating its robustness in handling both linear and non-linear classification tasks.

---
