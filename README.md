This project predicts customer churn for a telecom company using Machine Learning.
Customer churn refers to customers who stop using the company’s services. Predicting churn helps businesses take proactive steps to retain customers and reduce revenue loss.


Objective

Identify key factors influencing customer churn
Build predictive models using Machine Learning
Evaluate model performance using classification metrics
Provide business insights based on data


Dataset Information

7043 customer records
1 features including:
Demographics (Gender, SeniorCitizen, Partner, Dependents)
Services (InternetService, OnlineSecurity, StreamingTV, etc.)
Account info (Contract, PaymentMethod, MonthlyCharges, TotalCharges)
Target variable: Churn (Yes/No)


Technologies Used

Python
Pandas & NumPy
Scikit-learn
Matplotlib & Seaborn

Data Cleaning

Dropped unnecessary columns (customerID)
Converted TotalCharges to numeric
Handled missing values

2️ Feature Engineering

One-hot encoding for categorical variables
Feature scaling using StandardScaler

3️ Model Training

Logistic Regression
Random Forest Classifier

4️ Model Evaluation

Accuracy
Precision
Recall
F1-Score
Confusion Matrix
ROC Curve
