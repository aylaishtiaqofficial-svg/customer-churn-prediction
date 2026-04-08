This project focuses on predicting customer churn using machine learning techniques. The goal is to identify customers who are likely to leave a service so that businesses can take proactive steps to retain them.

The project includes data preprocessing, exploratory data analysis (EDA), and model building using Logistic Regression and Decision Tree.

Dataset used: Telco Customer Churn Dataset
It contains customer information such as:
Demographics
Account details
Services used
Churn status

Project Steps:
1. Data Preprocessing:
Handled missing values.
Converted categorical variables into numerical format.
Split data into training and testing sets.
2. Exploratory Data Analysis (EDA):
Analyzed relationships between features and churn.
Created multiple visualizations.
Identified key patterns such as:
Higher churn in low tenure customers.
Higher churn with higher monthly charges.
3. Model Building:
Two models were implemented:
Logistic Regression
Decision Tree Classifier
4. Model Evaluation:
Models were evaluated using:
Accuracy
Precision
Recall
F1-Score
Confusion Matrix

Results:
Logistic Regression
Accuracy: 0.983
Precision: 0.985
Recall: 0.955
F1-Score: 0.970
Decision Tree
Accuracy: 1.000
Precision: 1.000
Recall: 1.000
F1-Score: 1.000

Conclusion:
The Decision Tree achieved perfect scores but may suffer from overfitting.
Logistic Regression showed slightly lower but more reliable performance.

Recommended Model:
Logistic Regression is recommended due to better generalization on unseen data.

Future Improvements:
Apply cross-validation
Perform hyperparameter tuning
Try advanced models like Random Forest or XGBoost

Project Objective:
To help businesses identify customers at risk of churn and take preventive actions to improve customer retention.

Author:
Ayla Ishtiaq
