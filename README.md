ML_PROJECT
LOAN DEFAULT PREDICTION USING MACHINE LEARNING

This project aims to predict loan defaults using machine learning models, helping financial institutions streamline the loan approval process and manage credit risk more effectively. It explores multiple machine learning algorithms, including Logistic Regression, Support Vector Machine, Decision Tree, and K-Nearest Neighbors, to assess their predictive capabilities on a loan default dataset.

Project Overview
Loan default prediction is critical for financial institutions to minimize risk and make informed lending decisions. By using machine learning techniques, this project aims to predict whether a borrower will default on a loan based on features like credit history, income, debt-to-income ratio, and employment status.

Features
The dataset used in this project includes the following features:

age: Age of the borrower.
ed: Education level of the borrower.
employ: Years of employment.
address: Years at current address.
income: Annual income.
debtinc: Debt-to-income ratio.
creddebt: Credit debt.
otherdebt: Other debt.
default: Loan default status (0 = no default, 1 = default).
Dataset
The dataset used in this project consists of 1151 samples with 9 features and a binary target variable (default), which indicates whether the borrower defaulted on the loan.

Models
The following models were implemented and evaluated:

Logistic Regression
Support Vector Machine (SVM)
Decision Tree
K-Nearest Neighbors (KNN)

The models were assessed using the following metrics:
Accuracy, Precision, Recall,ROC-AUC Score


Results
The model performance summary is as follows:
Logistic regression with accuracy of 	80.98%
Support Vector Machine with accuracy of	82.06%
Decision Tree with the accuracy of 83.70%
K-Nearest Neighbors with the accuracy of 83.70%
The models show competitive accuracy, with Logistic Regression and K-Nearest Neighbors performing well in both accuracy and ROC-AUC metrics.
