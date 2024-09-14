# Machine Learning Internship Project: Online Payments Fraud Detection

This project focuses on developing a machine learning model to classify online payment transactions as either fraudulent or non-fraudulent. Using a dataset from Kaggle that includes historical transaction data, the goal is to identify patterns and features indicative of fraud. Key aspects of the project include preprocessing the data, training a classification model, and evaluating its performance to effectively detect fraudulent transactions. The final deliverable includes the project code, provided in a PDF format, demonstrating the application of machine learning techniques to enhance online payment security.

## This internship project includes both a minor and a major component:

1. Minor Project: I wrote a detailed report on "User Defined Functions in Python." The report is 7 pages long, typed, and submitted in PDF format. It delves into how user-defined functions work in Python, including their creation and practical applications.

2. Major Project: For the major project, I developed a machine learning model for Online Payment Fraud Detection. This involved classifying transactions as either fraudulent or non-fraudulent. I worked on data preprocessing, model training, and evaluating the model’s performance to ensure it effectively detects fraud. The project, including all relevant code and findings, was submitted in PDF format as per the instructions in the attached document.

The dataset consists of 10 variables:
* step: represents a unit of time where 1 step equals 1 hour
* type: type of online transaction
* amount: the amount of the transaction
* nameOrig: customer starting the transaction
* oldbalanceOrg: balance before the transaction
* newbalanceOrig: balance after the transaction
* nameDest: recipient of the transaction
* oldbalanceDest: initial balance of recipient before the transaction
* newbalanceDest: the new balance of recipient after the transaction
* isFraud: fraud transaction

## Python Libraries
pandas, numpy, seaborn, matplotlib, tabulate, sklearn

Random Forest and Naive Bayes were used to identify online payment fraud due to the large dataset.

## Conclusion
The best performing model is **Random Forest** for identifying fraudulent and non-fraudulent payments.
