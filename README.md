<p align="center">
  <a href="https://github.com/kazimbektas">
    <img src="https://miro.medium.com/v2/resize:fit:1400/1*Xj5QTBN7umWESE_YrrDlhw.png" alt="MasterHead"/>
  </a>
</p>

# Telco Customer Churn Prediction

## 1. Introduction

In today's competitive business environment, retaining customers is essential for maintaining profitability. High churn rates lead to significant revenue losses and increased costs in acquiring new customers. To address this challenge, this project aims to develop a machine learning model that accurately predicts customer churn. By identifying at-risk customers early, targeted retention strategies such as personalized offers and marketing can be employed to reduce churn, improve customer satisfaction, and ultimately enhance company profitability.

### 1.1 Business Problem
The goal of this project is to develop a machine learning model that can predict whether a customer is likely to churn (leave the company). This will enable the company to take proactive measures to retain customers.

### 1.2 Dataset Story
The Telco customer churn dataset contains information about 7,043 customers of a fictional telecommunications company in California during the third quarter. The dataset includes details about customer demographics, services subscribed to, account information, and whether the customer left the company (churned) or continued with the services.

### 1.3 Dataset Variables
- **CustomerId**: Unique identifier for each customer account
- **Gender**: Customer's gender (Male or Female)
- **SeniorCitizen**: Binary indicator for senior citizen status (1 for Yes, 0 for No)
- **Partner**: Whether the customer has a partner (Yes or No)
- **Dependents**: Whether the customer has dependents (Yes or No)
- **Tenure**: Number of months the customer has been with the company
- **PhoneService**: Whether the customer has phone service (Yes or No)
- **MultipleLines**: Whether the customer has multiple lines (Yes, No, or No phone service)
- **InternetService**: Type of internet service (DSL, Fiber optic, or No)
- **OnlineSecurity**: Whether the customer has online security (Yes, No, or No internet service)
- **OnlineBackup**: Whether the customer has online backup (Yes, No, or No internet service)
- **DeviceProtection**: Whether the customer has device protection (Yes, No, or No internet service)
- **TechSupport**: Whether the customer has tech support (Yes, No, or No internet service)
- **StreamingTV**: Whether the customer has streaming TV service (Yes, No, or No internet service)
- **StreamingMovies**: Whether the customer has streaming movies service (Yes, No, or No internet service)
- **Contract**: Type of customer contract (Month-to-month, One year, Two year)
- **PaperlessBilling**: Whether the customer prefers paperless billing (Yes or No)
- **PaymentMethod**: Customer's payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
- **MonthlyCharges**: Amount billed to the customer monthly
- **TotalCharges**: Total amount billed to the customer
- **Churn**: Indicates if the customer left the company (Yes or No)

## 2. Project Objective
The aim of this project is to predict customer churn using machine learning techniques. Various models will be compared for their accuracy in predicting churn. The models include:
- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **Gradient Boosting Classifier**
- **XGBoost**
- **LightGBM**

By evaluating and comparing the performance of these models, the most accurate one will be selected for predicting customer churn.
