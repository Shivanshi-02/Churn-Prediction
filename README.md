# 📉 Customer Churn Prediction using Machine Learning

## 📌 Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses. This project predicts whether a customer is likely to churn by analyzing customer demographics, service usage, billing information, and contract details.

The project follows a complete Machine Learning workflow including data preprocessing, exploratory data analysis, handling class imbalance, feature selection, model training, evaluation, and customer segmentation.

---

## 🎯 Objectives

- Predict customer churn accurately
- Identify key factors responsible for customer churn
- Compare multiple Machine Learning algorithms
- Handle imbalanced datasets using SMOTE
- Evaluate models using multiple performance metrics
- Segment customers using K-Means clustering

---

## 📂 Dataset

**Dataset:** Telco Customer Churn Dataset

The dataset contains customer information including:

- Customer Demographics
- Contract Type
- Monthly Charges
- Total Charges
- Internet Services
- Payment Method
- Tech Support
- Tenure
- Churn Label (Target Variable)

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- Imbalanced-Learn (SMOTE)
- CHAID
- K-Means Clustering

---

## 📊 Exploratory Data Analysis

Performed extensive EDA including:

- Missing Value Analysis
- Data Cleaning
- Distribution Analysis
- Count Plots
- Box Plots
- Correlation Analysis
- Customer Behavior Analysis

Important insights discovered include:

- Month-to-Month contracts have higher churn rates.
- Customers paying through Electronic Check tend to churn more.
- Higher monthly charges increase churn probability.
- Customers without Tech Support show significantly higher churn.

---

## ⚙️ Data Preprocessing

- Missing Value Handling
- Label Encoding
- Feature Selection
- Train-Test Split
- Standard Scaling
- SMOTE Oversampling for class balancing

---

## 🤖 Machine Learning Models

The following models were implemented and compared:

- Logistic Regression
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost
- CHAID Decision Tree

---

## 📈 Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report
- ROC Curve
- ROC-AUC Score
- Cross Validation

---

## 👥 Customer Segmentation

K-Means Clustering was performed to identify different customer groups for targeted retention strategies.

Steps included:

- Feature Scaling
- Elbow Method
- Optimal Cluster Selection
- Cluster Analysis


## 📌 Key Features

✔ End-to-End Machine Learning Pipeline

✔ Data Cleaning & Feature Engineering

✔ Multiple ML Model Comparison

✔ Class Imbalance Handling using SMOTE

✔ Customer Segmentation using K-Means

✔ ROC-AUC Performance Evaluation

✔ Business Insights through EDA

---

## 📚 Future Improvements

- Hyperparameter Optimization
- Deployment using Flask/FastAPI
- Interactive Dashboard
- Real-Time Prediction API
- Explainable AI using SHAP
