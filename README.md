# Customer-Churn-Prediction
This project focuses on predicting customer churn using Machine Learning techniques. The project follows a complete end-to-end ML workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and model saving.
A machine learning pipeline to predict customer churn based on behavior and service usage data from a telecom company. This project includes data preprocessing, feature engineering, model tuning, and evaluation using Python and Scikit-learn.

## Project Objective
The goal is to build a binary classification model that predicts whether a customer will churn (Yes or No). Churn prediction helps businesses reduce customer loss and improve retention strategies.

## Dataset Info
Source: IBM Telco Customer Churn Dataset
Rows: ~7,000 customers
Target: Churn column (Yes = churned, No = not churned)
Features: Gender, Contract type, Monthly charges, Tenure, etc.

## Results
Achieved a high AUC-ROC score showing good distinction between churned and retained customers.
Feature importance highlighted key factors like contract type, tenure, and monthly charges.

Customer churn is one of the biggest challenges faced by telecom companies. Retaining existing customers is significantly more cost-effective than acquiring new ones.

This project aims to build a Machine Learning model that predicts whether a customer is likely to churn based on historical customer data such as tenure, contract type, monthly charges, payment method, and other service-related features.
To preprocess and clean the dataset

To build and compare classification models

To evaluate model performance using appropriate metrics

To identify important features contributing to churn

📂 Dataset Information

Dataset Name: IBM Telco Customer Churn Dataset

Total Records: ~7,000 customers

Total Features: 20+ features

Target Variable: Churn

Yes → Customer left

No → Customer stayed

🔑 Key Features:

Gender

Senior Citizen

Tenure

Contract Type

Monthly Charges

Total Charges

Internet Service

Payment Method

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

🔍 Project Workflow
1️⃣ Data Preprocessing

Handled missing values

Converted categorical variables into numerical format

Feature encoding (Label Encoding / One-Hot Encoding)

Feature scaling where required

Train-Test split (e.g., 80% training, 20% testing)

2️⃣ Exploratory Data Analysis (EDA)

Churn distribution visualization

Relationship between tenure and churn

Contract type vs churn

Monthly charges vs churn

Correlation heatmap

Key Insight:
Customers with month-to-month contracts and higher monthly charges are more likely to churn.

3️⃣ Model Building

The following machine learning models were implemented:

Logistic Regression

Random Forest Classifier

(Add others if you used them)

4️⃣ Model Evaluation Metrics

Models were evaluated using:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

ROC-AUC Score

## Author
Ivan Lucas

