1.📝 Project Overview
Customer churn is a major challenge for telecom companies, leading to revenue loss and reduced customer lifetime value.
This project builds a machine learning classification model to predict whether a customer is likely to churn based on demographic details, service usage, and billing information.
The project follows an end-to-end data science workflow, from data preprocessing and exploratory data analysis (EDA) to model training, evaluation, and visualization.

2.🎯 Objective
Predict whether a customer will churn (Yes/No)
Identify key factors influencing customer churn
Evaluate model performance using accuracy and classification metrics
Provide insights to support customer retention strategies

3.📂 Dataset
Source: Kaggle – Telco Customer Churn Dataset
Records: 7,000+ customers
Target Variable: Churn

>> Key Features:
Customer demographics (gender, senior citizen, dependents)
Account information (tenure, contract type, payment method)
Services used (internet service, online security, streaming services)
Billing details (monthly and total charges)

4.🛠 Tech Stack
Programming Language: Python
Libraries:
Pandas, NumPy
Matplotlib, Seaborn

5.🔄 Project Workflow
Data Loading & Inspection
Data Cleaning
Handling missing values
Converting data types
Removing irrelevant columns
Exploratory Data Analysis (EDA)
Churn distribution analysis
Tenure, pricing, and contract-based insights
Correlation analysis
Feature Encoding
Label encoding of categorical variables
Model Building
Train-test split
Random Forest Classifier
Model Evaluation
Accuracy score
Precision, Recall, F1-score
Confusion matrix
Visualization
2D plots for churn insights
3D visualization for multivariate analysis

6.📊 Visualizations Included
Churn distribution count plot
Churn vs tenure box plot
Monthly charges vs churn
3D scatter plot (Tenure vs Monthly Charges vs Churn)
Scikit-learn
Environment: Jupyter Notebook

7.Model Performance
Algorithm Used: Random Forest Classifier
Accuracy: ~78–82% (may vary based on random state and preprocessing)
Strong performance in identifying high-risk churn customers

8.💡 Key Insights
Customers with short tenure are more likely to churn
High monthly charges increase churn probability
Long-term contracts significantly reduce churn
Tenure and monthly charges are among the most influential features
