💲 Fraud Detection Using Machine Learning

A practical machine learning project that detects fraudulent financial transactions in real-time. This project demonstrates how advanced classification algorithms can significantly reduce financial fraud by identifying suspicious activities with high accuracy.

📌 Project Overview

Fraudulent activities in digital payments and mobile banking systems can lead to severe financial losses. This project builds and evaluates multiple machine learning models to automatically flag potentially fraudulent transactions based on behavioral and financial patterns.

Objectives:

Build a robust supervised ML model for fraud detection.
Compare multiple algorithms for predictive performance.
Assess the financial and operational impact of the model.
🧠 Machine Learning Workflow

1. Data Exploration (EDA)

Analyzed Fraud_Analysis_Dataset.csv to understand data distribution and imbalance.
Investigated transaction types (CASH-IN, CASH-OUT, TRANSFER, etc.).
Visualized fraud proportions and correlations using Matplotlib and Seaborn.
2. Feature Engineering

Encoded categorical variables (type).
Scaled continuous features using StandardScaler.
Derived additional features such as transaction deltas and ratios to improve fraud signal strength.
3. Model Development

Trained and compared the following models:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Gradient Boosting
XGBoost
4. Model Evaluation

Evaluated models using key classification metrics:

Accuracy
Precision
Recall
F1-Score
ROC-AUC Score
Emphasis was placed on precision (to reduce false positives) and recall (to minimize undetected fraud).

📊 Model Performance Comparison

Model	Accuracy	Precision	Recall	F1-Score	ROC-AUC
Logistic Regression	0.9861	0.9950	0.8684	0.9274	0.9724
Decision Tree	0.9960	0.9867	0.9737	0.9801	0.9861
Random Forest	0.9960	1.0000	0.9605	0.9799	0.9999
Gradient Boosting	0.9964	1.0000	0.9649	0.9821	0.9996
XGBoost	0.9982	1.0000	0.9825	0.9912	1.0000
✅ XGBoost achieved the best overall performance with a near-perfect ROC-AUC of 1.0000.

