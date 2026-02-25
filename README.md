# Loan Approval Prediction System 🚀

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange)](https://scikit-learn.org/)

An automated classification system designed to predict whether a loan applicant should be **Approved** or **Rejected** based on their financial profile and credit history.

## 📌 Project Overview
This project utilizes Machine Learning to streamline the decision-making process for loan applications. The model analyzes various applicant features such as annual income, loan amount, CIBIL (credit) score, and asset values to provide a reliable "Approved" or "Rejected" status.

## 📊 Dataset Attribution
The data used in this project is sourced from Kaggle:
- **Dataset:** [Loan Approval Prediction Dataset](https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset)
- **Author:** Archit Sharma

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn
- **Serialization:** Joblib (for saving the model and scaler)

## 📁 Project Structure
```text
.
├── Data/                   # Raw and cleaned datasets
├── Notebooks/              # Analysis, EDA, and model training
├── model/                  # Serialized production-ready files (.pkl)
│   ├── model_loan_rf.pkl   # Trained Random Forest model
│   └── scaler_loan.pkl     # Fitted StandardScaler for input normalization
└── README.md
