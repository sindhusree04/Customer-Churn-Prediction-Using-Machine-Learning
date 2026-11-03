# Customer Churn Prediction Using Machine Learning

## 1. Project Overview

Customer Churn Prediction is a Machine Learning project that predicts whether a customer is likely to leave a telecom service provider. This project uses historical customer data to identify patterns and understand the factors that influence customer churn.

The main aim is to build a Machine Learning classification model that helps businesses identify customers who may discontinue their services and take steps to improve customer retention.

## 2. Problem Statement

In the telecommunications industry, retaining existing customers is an important business challenge. Customers may discontinue their services due to various factors, such as contract type, monthly charges, tenure, payment methods, and services used.

Identifying customers who are likely to leave can be difficult through manual analysis.

This project uses Machine Learning techniques to predict customer churn based on customer information and service-related features.

## 3. Project Objectives

- Understand customer data and identify churn patterns.
- Perform data cleaning and preprocessing.
- Explore relationships between customer features and churn.
- Build and evaluate different Machine Learning classification models.
- Compare model performance and select the best-performing model.
- Develop a user-friendly web application using Gradio.

## 4. Dataset Description

The dataset is the **Telco Customer Churn Dataset**, available on Kaggle.

**Dataset Link:** https://www.kaggle.com/datasets/blastchar/telco-customer-churn

The dataset contains 7,043 customer records and 21 columns, including customer details, subscribed services, account information, and churn status.

### Dataset Columns

| Column | Description |
|---|---|
| customerID | Unique customer identification number |
| gender | Customer's gender |
| SeniorCitizen | Indicates whether the customer is a senior citizen |
| Partner | Whether the customer has a partner |
| Dependents | Whether the customer has dependents |
| tenure | Number of months the customer has stayed |
| PhoneService | Whether phone service is subscribed |
| MultipleLines | Whether multiple phone lines are used |
| InternetService | Type of internet service |
| OnlineSecurity | Whether online security is subscribed |
| OnlineBackup | Whether online backup is subscribed |
| DeviceProtection | Whether device protection is subscribed |
| TechSupport | Whether technical support is subscribed |
| StreamingTV | Whether streaming TV is subscribed |
| StreamingMovies | Whether streaming movies is subscribed |
| Contract | Type of customer contract |
| PaperlessBilling | Whether paperless billing is enabled |
| PaymentMethod | Customer's payment method |
| MonthlyCharges | Monthly amount charged |
| TotalCharges | Total amount charged |
| Churn | Indicates whether the customer left the service |

## 5. Technologies and Libraries Used

- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **Scikit-learn** – Machine Learning model building and evaluation
- **Pickle** – Model saving and loading
- **Gradio** – Web application development
- **Jupyter Notebook** – Development environment

## 6. Machine Learning Workflow

The project follows these steps:

1. Business Understanding and Problem Statement
2. Data Loading and Understanding
3. Data Preprocessing and Cleaning
4. Exploratory Data Analysis (EDA)
5. Feature Selection
6. Train-Test Split
7. Feature Encoding and Scaling
8. Model Building and Training
9. Model Evaluation and Comparison
10. Best Model Selection
11. Model Saving and Loading
12. Gradio Application Development

## 7. Machine Learning Problem Type

This project is a **Supervised Machine Learning – Classification Problem** because the target variable, `Churn`, contains two categories: Yes and No.

- **Input:** Customer details, service information, contract type, tenure, and billing information.
- **Output:** Predicted customer churn status (Yes or No).

The target variable is encoded as:
- No → 0
- Yes → 1

### Machine Learning Algorithms Used

The following classification algorithms are implemented:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier

## 8. Model Evaluation Metrics

The models are evaluated using the following metrics:

- **Accuracy:** Measures the overall percentage of correct predictions.
- **Precision:** Measures how many customers predicted as churn actually churned.
- **Recall:** Measures how many actual churn customers were correctly identified.
- **F1-Score:** Represents the balance between precision and recall.

The models are compared using these evaluation metrics, and the best-performing model is selected based on its F1-score.

## 9. Expected Output

The final application allows users to enter customer details, including tenure, contract type, monthly charges, payment method, internet service, and other service-related information.

Based on the provided details, the trained Machine Learning model predicts whether the customer is likely to leave the telecom service or continue using it.

The application is developed using Gradio to provide a simple and user-friendly interface.

## 10. Conclusion

This project demonstrates how Machine Learning can be applied to a real-world business problem in the telecommunications industry. It helps identify customers who are likely to discontinue their services by analyzing customer characteristics and service-related information.

Through this project, I gained practical experience in the complete Machine Learning workflow, including data preprocessing, exploratory data analysis, feature encoding, model building, evaluation, model selection, and application development using Gradio.

**Project Domain:** Machine Learning / Data Science

**Project Title:** Customer Churn Prediction Using Machine Learning
