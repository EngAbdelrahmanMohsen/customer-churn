# Telco Customer Churn Prediction

## Overview
This project focuses on predicting customer churn for a telecommunications company using the Telco Customer Churn dataset. The analysis involves data preprocessing, handling imbalanced data, training a Random Forest Classifier, and optimizing the model using GridSearchCV. The goal is to identify customers likely to churn and evaluate the model's performance using metrics such as accuracy, precision, recall, F1 score, and AUC-ROC.

## Dataset
The dataset used is `WA_Fn-UseC_-Telco-Customer-Churn.csv`, which contains customer information such as demographics, services subscribed, billing details, and churn status. Key features include:
- **CustomerID**: Unique identifier for each customer
- **Demographics**: Gender, SeniorCitizen, Partner, Dependents
- **Services**: PhoneService, MultipleLines, InternetService, OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies
- **Billing**: Contract, PaperlessBilling, PaymentMethod, MonthlyCharges, TotalCharges
- **Churn**: Target variable indicating whether the customer churned (Yes/No)

## Project Structure
- `CustomerChurn.ipynb`: Jupyter Notebook containing the complete analysis, including data loading, preprocessing, model training, evaluation, and hyperparameter tuning.
- `WA_Fn-UseC_-Telco-Customer-Churn.csv`: Dataset file (not included in the repository; download from [Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn)).
- `README.md`: This file, providing an overview and instructions for the project.

## Requirements
To run the notebook, you need the following Python libraries:
- pandas
- scikit-learn
- imblearn
- numpy

You can install the dependencies using:
```bash
pip install pandas scikit-learn imbalanced-learn numpy
