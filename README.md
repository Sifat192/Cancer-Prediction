# Cancer Prediction using Logistic Regression

## Overview

This project develops a machine learning model to predict the likelihood of cancer using clinical and biological patient data. The goal is to classify whether a patient is likely to have cancer based on various medical indicators.

The model is implemented using **Logistic Regression**, a supervised learning algorithm commonly used for binary classification problems.

---

## Problem Statement

Early cancer detection is critical for improving treatment outcomes. By analyzing patient medical attributes such as biological markers, genetic factors, and health indicators, machine learning models can assist in identifying potential cancer cases.

This project demonstrates the use of a machine learning pipeline to build a predictive model for cancer diagnosis.

---

## Dataset

The dataset contains patient medical records with multiple clinical and biological features.

**Dataset Characteristics**

* Observations: 260,000 records
* Features used for training: 11
* Target Variable: `Appendix_Cancer_Prediction`

### Selected Predictive Features

* Age
* BMI
* Family_History_Cancer
* Genetic_Mutations
* Radiation_Exposure
* Blood_Pressure
* Cholesterol_Level
* White_Blood_Cell_Count
* Red_Blood_Cell_Count
* Platelet_Count
* Tumor_Markers

These variables represent patient health indicators and biological measurements that may influence cancer risk.

---

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Jupyter Notebook

---

## Machine Learning Workflow

The project follows a standard machine learning pipeline:

```
Dataset
   ↓
Data Preprocessing
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Logistic Regression Model
   ↓
Model Evaluation
```

---

## Data Preprocessing

The following preprocessing steps were applied:

* Feature selection
* Handling dataset imbalance
* Train-test split (80% training, 20% testing)
* Feature scaling using **StandardScaler**

Feature scaling ensures that all features contribute equally during model training.

---

## Model

The model used in this project is **Logistic Regression**, a linear classification algorithm that estimates the probability of a binary outcome using the logistic (sigmoid) function.

Logistic Regression is widely used in healthcare analytics for risk prediction tasks.

---

## Model Evaluation

Model performance was evaluated using several classification metrics:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

Accuracy alone is not sufficient for imbalanced datasets, therefore additional evaluation metrics were used to better understand model performance.

---

## Results

| Metric    | Value |
| --------- | ----- |
| Accuracy  | ~50%  |
| Recall    | ~0.49 |
| Precision | ~0.50 |
| F1 Score  | ~0.50 |

The model provides moderate predictive capability. The results indicate the difficulty of predicting cancer outcomes using limited clinical features and highlight the impact of class imbalance in healthcare datasets.

---

## Visualizations

The project includes the following visualizations:

* Confusion Matrix
* Feature Importance (Logistic Regression Coefficients)

These visualizations help interpret the model and understand which features influence predictions.

---

## Key Learnings

This project demonstrates:

* Supervised machine learning for healthcare prediction
* Logistic Regression implementation
* Handling imbalanced datasets
* Model evaluation using multiple metrics
* Feature importance interpretation

---

## Future Improvements

Possible improvements include:

* Hyperparameter tuning
* Advanced feature engineering
* Testing more complex models such as tree-based algorithms
* Ensemble methods for improved predictive performance

---

## Author



