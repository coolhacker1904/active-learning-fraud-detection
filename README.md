# Active Learning for Credit Card Fraud Detection

## Overview

This project explores Active Learning techniques for detecting fraudulent credit card transactions while reducing labeling effort.

Instead of labeling the entire dataset, the model selectively queries the most informative samples to improve performance efficiently.

## Features

- Credit card fraud detection
- Handling class imbalance using SMOTE
- Active Learning implementation
- Entropy Sampling
- Margin Sampling
- Random Sampling baseline
- Model explainability using SHAP
- Performance comparison using ROC-AUC and F1 Score

## Technologies Used

- Python
- Scikit-Learn
- XGBoost
- SHAP
- SMOTE
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Workflow

1. Data preprocessing and feature scaling
2. Class balancing using SMOTE
3. Baseline model comparison
4. Active Learning iterations
5. Performance evaluation
6. SHAP-based feature importance analysis

## Results

- Active Learning reduced labeling requirements.
- Entropy Sampling achieved strong performance among the evaluated strategies.
- XGBoost provided reliable fraud detection performance.
- SHAP improved model interpretability.

## Concepts Used

- Machine Learning
- Active Learning
- Fraud Detection
- Imbalanced Classification
- Explainable AI
- Ensemble Learning
