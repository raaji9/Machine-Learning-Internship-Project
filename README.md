# 💳 Machine Learning Internship Project: Online Payments Fraud Detection

This project focuses on developing a machine learning model to classify online payment transactions as either fraudulent or non-fraudulent. Utilizing a dataset from Plasmid that includes historical transaction data, the goal is to identify patterns and features indicative of fraud. Key aspects of the project include data preprocessing, training a classification model, and evaluating its performance to effectively detect fraudulent transactions. The final deliverable includes the project code and findings, provided in PDF format, demonstrating the application of machine learning techniques to enhance online payment security.

## 📊 Project Components

This internship project consists of both a minor and a major component:

### 1. 📄 Minor Project
I authored a detailed report on **User Defined Functions in Python**. This 7-page document explores how user-defined functions operate in Python, including their creation and practical applications.

### 2. 🚀 Major Project
For the major project, I developed a machine learning model for **Online Payment Fraud Detection**. This involved classifying transactions as either fraudulent or non-fraudulent. My work included:

- **Data Preprocessing:** Cleaning and transforming the dataset for analysis.
- **Model Training:** Implementing various classification algorithms.
- **Model Evaluation:** Assessing the model’s performance to ensure effective fraud detection.

The project, including all relevant code and findings, was submitted in PDF format as per the instructions in the attached document.

## 📋 Dataset Overview

The dataset consists of 10 variables:

| Variable           | Description                                           |
|--------------------|-------------------------------------------------------|
| `step`             | Represents a unit of time (1 step = 1 hour)         |
| `type`             | Type of online transaction                            |
| `amount`           | Amount of the transaction                             |
| `nameOrig`         | Customer initiating the transaction                   |
| `oldbalanceOrg`    | Balance before the transaction                        |
| `newbalanceOrig`   | Balance after the transaction                         |
| `nameDest`         | Recipient of the transaction                          |
| `oldbalanceDest`   | Initial balance of recipient before the transaction   |
| `newbalanceDest`   | New balance of recipient after the transaction        |
| `isFraud`         | Indicates if the transaction is fraudulent (1 = yes, 0 = no) |

## 📚 Python Libraries Used

- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `tabulate`
- `sklearn`

A basic machine learning pipeline was implemented to classify fraudulent online payments using the given dataset.

## 🚀 Conclusion

The **RandomForestClassifier** demonstrated the effectiveness of machine learning in detecting fraudulent transactions based on historical data. This project highlights the potential of advanced analytical techniques to improve online payment security and reduce financial fraud.

---
