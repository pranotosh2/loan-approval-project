# Loan Approval Prediction Project

This project is focused on predicting loan approvals using Machine Learning techniques. The workflow includes data preprocessing, exploratory data analysis (EDA), model building, and evaluation.

**Project Overview**

The project explores customer loan applications and analyzes factors such as gender, marital status, income, and loan amount to understand approval patterns. Machine Learning models are then applied to predict loan approval status.

**Workflow**

Data Preprocessing

- Handle missing values

- Encode categorical variables (Label Encoding / One-Hot Encoding)


Exploratory Data Analysis (EDA)

 - Distribution of approved vs. rejected loans

- Loan approval trends by gender, marital status, income levels, and credit history

- Correlation analysis between features

Feature Engineering

- Combine income features (Total Income)

- Avoid outlier by transforming some features into log-normal transformation


Model Training

- Logistic Regression

- Decision Tree Classifier

- Random Forest Classifier

- Support Vector Machine (SVM)

- XGBoost
  
- KNN

Model Evaluation

- Accuracy

-  Classification Report (Precision, Recall, F1-Score)

 - Confusion Matrix

Tech Stack

- Programming Language: Python

- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

- Environment: Jupyter Notebook

Run all cells to reproduce results.

Results

Key Finding: Credit history and applicant income were the most influential features.

Best Model: Random Forest Classifier achieved the highest accuracy.

Performance Metrics:

Accuracy: ~79% 

Precision, Recall, and F1-score reported for comparison across models.

Sample Visuals

- Loan approval rate by gender and marital status

- Income distribution of approved vs. rejected applicants

- Feature importance chart from Random Forest



