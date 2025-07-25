# 🏦 Credit Risk Modelling (Machine Learning Project)

This project focuses on building a machine learning model to assess credit risk by predicting the probability of a borrower defaulting. It includes the full ML pipeline — data preprocessing, feature engineering, model training, evaluation, and deployment using Streamlit.

---

## 📌 Table of Contents

1. [Project Overview](#project-overview)  
2. [Features](#features)  
3. [Project Structure](#project-structure)  
4. [Installation & Setup](#installation--setup)  
5. [Usage Guide](#usage-guide)  
6. [Model & Methodology](#model--methodology)  
7. [Results & Metrics](#results--metrics)  
8. [Interpretability](#interpretability)  
9. [Customization](#customization)  
10. [Contributing](#contributing)  
11. [License](#license)  

---

## 📖 Project Overview

The main objective of this project is to help lenders assess creditworthiness by developing a machine learning model that identifies potential defaulters. This model aids in reducing financial risk and improving lending decisions.

---

## 🚀 Features

- Data preprocessing with missing value handling and encoding
- Class imbalance treatment using SMOTE or undersampling
- Multiple model training: Logistic Regression, Random Forest, XGBoost
- Hyperparameter tuning with Optuna or GridSearchCV
- Evaluation with ROC-AUC, Gini, KS statistic, decile analysis
- Model explainability using SHAP and LIME
- Streamlit app for interactive prediction and visualization

---

## 🗂️ Project Structure
credit_risk_modelling_ml/
│
├── notebooks/              # EDA, feature engineering, modeling experiments
├── data/                   # Raw and processed datasets (CSV/Parquet)
├── src/
│   ├── preprocess.py       # Data cleaning and transformation routines
│   ├── feature_engineering.py
│   ├── model_train.py      # Training and validation code
│   ├── evaluate.py         # Metrics and decile analysis
│   ├── explain.py          # SHAP and LIME explainability utilities
│   └── predict.py          # Utility to score new borrower instances
├── model/                  # Saved model artifacts: .pkl, .json, hyperparameters
├── app/
│   └── main.py             # Streamlit app for interactive risk inference
├── requirements.txt
├── README.md
└── LICENSE


