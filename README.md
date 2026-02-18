📊 Telecom Customer Churn Prediction
📌 Project Overview

This project focuses on predicting customer churn for a Telecom company using Machine Learning models. The main objective is to identify key factors influencing churn and provide actionable business insights.

Customer churn prediction helps telecom companies reduce customer loss and improve retention strategies.

🎯 Objective

Predict whether a customer will churn or not.

Apply data preprocessing techniques (Encoding & Scaling).

Train and evaluate Logistic Regression and Random Forest models.

Identify the most influential feature affecting churn.

Provide business recommendations based on model insights.

📂 Dataset Information

Total Records: 2500+

Features: 7 Independent Variables

Target Variable: Churn (Yes / No)

🔢 Numerical Features

Tenure_Months

Monthly_Charges

Total_Charges

🏷️ Categorical Features

Contract_Type

Internet_Service

Payment_Method

🧹 Data Preprocessing

Checked for missing values

Applied Label Encoding to categorical variables

Applied Standard Scaling to numerical features

Split dataset into Training and Testing sets (Train-Test Split)

🤖 Models Used
1️⃣ Logistic Regression

Used for classification

Interpretable model (Coefficient analysis)

Helped identify key churn factors

2️⃣ Random Forest Classifier

Ensemble learning method

Handles non-linearity well

Provides feature importance

📊 Model Evaluation Metrics

Confusion Matrix

Accuracy Score

Precision

Recall

F1-Score

🔍 Key Insight

After analyzing the Logistic Regression coefficients:

Poor Internet Service was identified as the most influential factor affecting customer churn.

Customers experiencing poor internet connectivity are more likely to leave the telecom company.
