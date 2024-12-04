# Telecom Customer Churn Prediction using XGBoost

A machine learning project that predicts customer churn for an Iranian telecom provider using XGBoost (eXtreme Gradient Boosting). The model achieves exceptional performance with an AUC-ROC score of 0.9955 and accuracy of 97.78%.

## Overview

This project analyzes customer churn in the telecommunications industry using a dataset from an Iranian telecom provider. The model identifies customers likely to discontinue services and highlights key factors contributing to churn, enabling targeted retention strategies.

### Key Features

- Implements XGBoost algorithm for binary classification
- Handles class imbalance using scale_pos_weight
- Uses 5-fold cross-validation for robust model evaluation
- Provides comprehensive feature importance analysis
- Achieves high accuracy in churn prediction

## Model Performance

| Metric | Value |
|--------|--------|
| AUC-ROC | 0.9955 |
| F1 Score | 0.9320 |
| Precision | 0.9057 |
| Accuracy | 0.9778 |
| True Positive Rate | 0.9600 |
| True Negative Rate | 0.9811 |

## Dataset

The dataset comprises 3,150 customer records with 14 variables including:
- Call and SMS usage metrics
- Customer complaints
- Service failures
- Subscription length
- Account status

Data is aggregated over 9 months, with churn status determined at the 12-month mark.
