# End-to-End-Telecom-Customer-Churn-Prediction-System-with-XGBoost-and-Streamlit-Deployment
This project predicts whether a telecom customer is likely to churn using Machine Learning. It includes complete data preprocessing, model training, evaluation, and deployment as an interactive web application.

An end-to-end Machine Learning project that predicts customer churn in the telecom industry using XGBoost and deploys the model as an interactive Streamlit web application.

This project covers the complete ML pipeline:
Data preprocessing → Feature engineering → Model training → Evaluation → Deployment.

# Project Overview

Customer churn is one of the biggest challenges in the telecom industry.
This system predicts whether a customer is likely to leave the service based on demographic, service usage, and billing information.

The application provides:

Real-time churn prediction

Probability score

Risk level (Low / Medium / High)

Visual probability comparison

 
# Dataset Information

7,043 telecom customer records

19 features

Target variable: Churn (Yes/No)

Includes demographic, service, and billing details

# Machine Learning Approach

Data Cleaning & Preprocessing

Label Encoding for categorical variables

Class imbalance handled using SMOTE

Model used: XGBoost Classifier

Train-Test Split

Evaluation using accuracy and probability scores

Test Accuracy: ~77%

📈 Key Predictors of Churn

Contract Type

Tenure Duration

Monthly Charges

Internet Service

Payment Method

# Deployment

The model is deployed using Streamlit with:

Interactive input fields

Real-time prediction

Confidence score

Risk classification

Probability visualization using Plotly

 # How to Run Locally

Clone the repository:

git clone <your-repo-link>
cd <repo-folder>

Install dependencies:

pip install -r requirements.txt

Run the Streamlit app:

streamlit run churn_app.py

# Business Impact

This system helps telecom companies:

Identify high-risk customers

Take proactive retention measures

Reduce revenue loss

Improve customer lifetime value
