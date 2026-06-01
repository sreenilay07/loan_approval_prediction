# Loan Approval Prediction System Using Machine Learning

## Project Overview

This project focuses on building a Loan Approval Prediction System using Machine Learning techniques in Python. The main objective of the project is to predict whether a loan application should be approved or rejected based on applicant information such as income, credit score, employment status, existing loans, and loan amount.

The project follows a complete machine learning workflow including dataset generation, data preprocessing, exploratory data analysis, visualization, model training, evaluation, and prediction.

A synthetic dataset containing 1500 applicant records was generated using NumPy and Pandas with realistic relationships between financial factors and loan approval decisions.

---

# Dataset Generation

The dataset was created programmatically using Python libraries such as NumPy and Pandas.

The dataset includes the following features:

* ApplicantID
* Gender
* Age
* MonthlyIncome
* LoanAmount
* CreditScore
* EmploymentStatus
* ExistingLoans
* LoanTerm
* PropertyArea
* LoanApproved

The approval logic was designed using realistic conditions such as:

* Higher income increases approval probability
* Higher credit scores improve approval chances
* Unemployed applicants have lower approval probability
* Applicants with multiple existing loans are considered higher risk

The final dataset contains 1500 records and was exported as a CSV file for further analysis and model training.

---

# Libraries and Tools Used

## Programming Language

* Python

## Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Development Environment

* Google Colab
* Jupyter Notebook

## Machine Learning Algorithms

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

---

# Data Preprocessing

The following preprocessing steps were performed on the dataset:

* Checked and handled missing values
* Removed duplicate records
* Encoded categorical variables using Label Encoding
* Removed unnecessary columns such as ApplicantID
* Applied feature scaling using StandardScaler
* Validated dataset structure and values

---

# Exploratory Data Analysis

Several analyses were performed to understand the dataset and identify important patterns affecting loan approval decisions.

The analysis showed that:

* Applicants with higher credit scores had a greater chance of loan approval
* Monthly income had a positive relationship with approval probability
* Unemployed applicants faced higher rejection rates
* Applicants with multiple existing loans were more likely to be rejected
* Loan amount and income showed noticeable correlations

---

# Data Visualizations

The following visualizations were created during the project:

* Bar chart showing loan approvals by employment status
* Correlation heatmap of numerical features
* Scatter plot of monthly income vs loan amount
* Pie chart showing approved and rejected applications

These visualizations helped in understanding relationships between financial factors and loan approval outcomes.

---

# Machine Learning Models

The dataset was divided into training and testing sets using train_test_split.

The following classification models were trained and evaluated:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

The models were evaluated using:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix

Among all models, Random Forest Classifier provided the best overall performance on the testing dataset.

---

# Model Performance Summary

The Random Forest model achieved the highest prediction accuracy and showed balanced performance across precision, recall, and F1-score metrics.

The trained model was then used to build a prediction system capable of predicting loan approval status based on user inputs.

---

# Prediction System

A console-based prediction system was created where users can enter applicant details such as:

* Age
* Monthly Income
* Loan Amount
* Credit Score
* Employment Status
* Existing Loans
* Loan Term
* Property Area

Based on the entered values, the system predicts whether the loan application will be:

* Approved
  or
* Rejected

The prediction system also includes input validation and error handling to prevent invalid data entry and program crashes.

---

# Steps to Run the Project

1. Download the project files
2. Open the Jupyter Notebook or Google Colab notebook
3. Install required libraries if needed
4. Run all notebook cells in sequence
5. Train the machine learning models
6. Execute the prediction system section
7. Enter applicant details to test predictions

---

# Project Files

* loan_approval.ipynb
* loan_approval_dataset.csv
* prediction_system.py
* README.md

---

# Conclusion

This project provided practical experience in machine learning workflows including synthetic dataset generation, preprocessing, visualization, classification modeling, evaluation, and prediction systems.

The project demonstrates how machine learning can assist financial institutions in making data-driven loan approval decisions more efficiently and accurately.
