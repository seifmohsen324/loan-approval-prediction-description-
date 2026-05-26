# 🏦 Loan Approval Prediction System

A Machine Learning project that predicts whether a loan application will be approved based on applicant information. The project focuses on solving a **binary classification problem** while handling **missing values**, **categorical data**, and **imbalanced datasets**.

---

## 📌 Project Overview

Loan approval is a critical task in financial institutions. Manual evaluation can be time-consuming and prone to bias. This project uses Machine Learning techniques to automate loan approval prediction by analyzing applicant-related features and generating predictions.

The project includes:

- Data preprocessing
- Missing value handling
- Encoding categorical features
- Handling class imbalance
- Training classification models
- Model evaluation using classification metrics

---

## 🎯 Objectives

- Predict whether a loan application will be approved or not
- Build and compare classification models
- Handle missing values effectively
- Encode categorical variables
- Address class imbalance issues
- Evaluate model performance using appropriate metrics

---

## 🧰 Technologies & Libraries

<div align="left">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

</div>

---

## 📂 Dataset

Dataset used:

**Loan Approval Prediction Dataset (Kaggle)**

The dataset contains applicant information such as:

- Gender
- Marital Status
- Education
- Income
- Loan Amount
- Credit History
- Employment Status
- Property Area
- Loan Term
- Loan Approval Status

---

## ⚙️ Project Workflow

### 1. Data Collection
- Load the dataset
- Explore features and target variable

### 2. Data Preprocessing
- Handle missing values
- Remove inconsistencies
- Feature engineering (if needed)

### 3. Encode Categorical Variables
Examples:
- Label Encoding
- One-Hot Encoding

### 4. Handle Imbalanced Data
Techniques used:

- SMOTE (Synthetic Minority Oversampling Technique)
- Class balancing methods

---

## 🤖 Models Used

### Logistic Regression
- Fast and interpretable
- Works well for binary classification

### Decision Tree
- Handles non-linear relationships
- Easy visualization and interpretation

Comparison performed between both models.

---

## 📊 Evaluation Metrics

Since loan datasets can be imbalanced, accuracy alone is not enough.

Metrics used:

- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## 🔍 Covered Concepts

- Binary Classification
- Data Preprocessing
- Missing Value Handling
- Feature Encoding
- Class Imbalance
- SMOTE
- Model Training
- Model Evaluation

---

## 🚀 How to Run

Clone repository:

```bash
git clone https://github.com/yourusername/loan-approval-prediction.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run notebook:

```bash
jupyter notebook
```

or run:

```bash
python main.py
```

---

## 📈 Future Improvements

- Hyperparameter tuning
- Try Random Forest and XGBoost
- Build a web interface using Flask/Streamlit
- Deploy the model
- Improve performance with feature selection

---

## 📸 Sample Pipeline

Dataset → Cleaning → Encoding → Balancing → Training → Evaluation → Prediction

---

## 👨‍💻 Author

**Saif Fattah**

Computer Engineering Student | AI & Machine Learning Enthusiast

GitHub: https://github.com/seifmohsen324

---
⭐ If you found this project useful, consider giving it a star.
