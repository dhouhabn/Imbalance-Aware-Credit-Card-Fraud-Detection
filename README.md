# Imbalance-Aware Credit Card Fraud Detection Using XGBoost and SMOTE with Hyperparameter Optimization

## Description

This repository contains the source code and reproducibility materials associated with the research study:

"Imbalance-aware credit card fraud detection using XGBoost and Synthetic Minority Over-sampling Technique with hyperparameter optimization."

The project investigates the use of XGBoost combined with Synthetic Minority Over-sampling Technique (SMOTE) and hyperparameter optimization for detecting fraudulent credit card transactions in highly imbalanced data.

The implementation includes data preprocessing, class-imbalance handling using SMOTE, XGBoost model training, hyperparameter optimization, model evaluation, and visualization of experimental results.

---

## Dataset Information

The study uses a publicly available credit card fraud detection dataset.

The dataset contains credit card transactions with a binary target variable indicating whether a transaction is fraudulent or legitimate.

Due to dataset licensing and redistribution restrictions, the original dataset is not included in this repository.

Researchers should obtain the dataset directly from the original source and place it in the appropriate data directory.

Expected structure:

data/
└── creditcard.csv

---

## Code Information

The code is implemented in Python.

The main components include:

- Data loading and validation
- Data preprocessing
- Feature and target separation
- Train/test splitting
- Class-imbalance analysis
- SMOTE-based oversampling
- XGBoost model training
- Hyperparameter optimization
- Model evaluation
- Performance visualization

---

## Requirements

The experiments were implemented using Python.

The main dependencies include:

- Python 3.10.12
- pandas 2.0.3
- NumPy 1.24.4
- scikit-learn 1.3.2
- imbalanced-learn 0.11.0
- XGBoost 2.0.3
- matplotlib 3.9.2
- seaborn 0.13.2
- scipy 1.14.1


requirements.txt

---

## Installation

Create a Python environment and install the required packages:

```bash
pip install -r requirements.txt
