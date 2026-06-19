# CreditWise – Loan Approval Prediction System

## Overview

CreditWise is a Machine Learning project that predicts whether a loan application should be approved based on an applicant's financial and demographic information. The project focuses on data preprocessing, feature engineering, model comparison, and training classification models to identify the most effective approach for loan approval prediction.

The trained model is saved as a `.pkl` file using Joblib, allowing it to be reused for future predictions without retraining.

---

## Features

* Data cleaning and preprocessing
* Missing value imputation
* Categorical feature encoding
* Feature engineering
* Feature scaling
* Training and evaluation of multiple machine learning models
* Comparison of model performance
* Model serialization using Joblib

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Joblib

---

## Dataset

The dataset contains applicant information such as:

* Applicant Income
* Coapplicant Income
* Employment Status
* Age
* Marital Status
* Dependents
* Credit Score
* Existing Loans
* Debt-to-Income Ratio (DTI)
* Savings
* Collateral Value
* Loan Amount
* Loan Term
* Loan Purpose
* Property Area
* Education Level
* Gender
* Employer Category

The target variable is **Loan_Approved**.

---

## Machine Learning Pipeline

1. Data preprocessing
2. Missing value handling
3. Feature encoding
4. Feature engineering
5. Feature scaling
6. Model training
7. Model evaluation
8. Model serialization

---

## Models Implemented

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Naive Bayes
* Random Forest
* XGBoost

---

## Best Performing Model

**XGBoost**

Performance achieved:

* Accuracy: 92%
* Precision: 83.6%
* Recall: 91.8%
* F1-Score: 87.5%

---

## Project Structure

```text
CreditWise-Loan-Approval/
│
├── data/
│   └── loan_approval_data.csv
│
├── models/
│   └── xgboost_model.pkl
│
├── notebooks/
│   └── CreditWise.ipynb
│
├── train_model.py
├── requirements.txt
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Suraj16032005/CreditWise-Loan-Approval.git
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Run the training script:

```bash
python train_model.py
```

---

## Future Improvements

* Build a web interface using Streamlit or Flask
* Perform hyperparameter tuning
* Add explainability using SHAP or LIME
* Deploy the trained model as a REST API
* Containerize the application using Docker

---

## Author

Suraj Nair
