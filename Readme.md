# 💳 Credit Card Fraud Detection Using Machine Learning

## 📌 Project Overview

Credit Card Fraud Detection is a binary classification problem where the objective is to classify transactions as either **fraudulent** or **legitimate**.

In this project, a **Random Forest Classifier** is used to detect fraudulent transactions based on transaction-related features. The model learns patterns from historical transaction data and predicts whether a new transaction is likely to be fraud or not.

Since fraud datasets are usually imbalanced, model performance is evaluated using multiple evaluation metrics instead of relying only on accuracy.

---

## 🎯 Problem Statement

With the increasing number of online transactions, detecting fraudulent activities has become an important challenge for financial institutions.

The goal of this project is to develop a machine learning model that can:

* Detect fraudulent transactions
* Classify transactions accurately
* Analyze transaction patterns
* Reduce incorrect fraud predictions

---

## 📂 Dataset Information

The dataset contains transaction details used for fraud classification.

Features include:

* Transaction amount
* Transaction hour
* Merchant category
* Foreign transaction indicator
* Location mismatch
* Device trust score
* Transaction frequency
* Cardholder age

### Target Variable

| Value | Meaning                |
| ----- | ---------------------- |
| 0     | Legitimate Transaction |
| 1     | Fraudulent Transaction |

---

# 🛠️ Technologies Used

### Programming Language

* Python

### Libraries Used

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

# 🔍 Exploratory Data Analysis

The following analysis was performed:

* Dataset information checking
* Checking missing values
* Checking duplicate records
* Understanding feature distributions
* Visualizing fraud and non-fraud transaction distribution
* Correlation analysis

---

# 🧹 Data Preprocessing

The following preprocessing techniques were applied:

### 1. Data Cleaning

* Checked missing values
* Removed unnecessary columns
* Prepared dataset for model training

### 2. Feature Encoding

Categorical features were converted into numerical values using:

* One Hot Encoding

### 3. Feature Scaling

Numerical features were standardized using:

* StandardScaler

This ensures all numerical features are on a similar scale and improves model performance.

---

# 🤖 Machine Learning Model

## Random Forest Classifier

Random Forest is an ensemble learning algorithm that combines multiple decision trees to make predictions.

It was selected because:

* It can capture complex patterns in transaction data
* It handles non-linear relationships effectively
* It works well with tabular datasets

---

# 📊 Model Evaluation

The trained model was evaluated using the following metrics:

## Accuracy

Measures the percentage of correctly classified transactions.

## Precision

Measures how many predicted fraud transactions were actually fraudulent.

## Recall

Measures how many actual fraud transactions were successfully detected.

## F1 Score

Provides a balance between precision and recall.

## ROC-AUC Score

Measures the ability of the model to distinguish between fraud and legitimate transactions.

---

# 🚀 Project Workflow

```
Dataset
   |
   ↓
Data Cleaning
   |
   ↓
Exploratory Data Analysis
   |
   ↓
Feature Encoding
   |
   ↓
Feature Scaling
   |
   ↓
Train-Test Split
   |
   ↓
Random Forest Model Training
   |
   ↓
Model Evaluation
   |
   ↓
Fraud Prediction
```

---

# 📁 Project Structure

```
Credit-Card-Fraud-Detection/

│
├── credit_card_fraud_10k.csv
│
├── Credit_Card_Fraud_Detection.ipynb
│
└── README.md
```

---

# 🔮 Future Improvements

Possible improvements for this project:

* Hyperparameter tuning using GridSearchCV or RandomizedSearchCV
* Handling class imbalance using SMOTE or class weights
* Comparing multiple machine learning algorithms
* Deploying the model using Flask/FastAPI
* Adding real-time fraud prediction

---

# 👨‍💻 Author

**Debmalyaa Dey**

Machine Learning Project
Credit Card Fraud Detection

---

# ⭐ Conclusion

This project demonstrates the application of machine learning for detecting fraudulent credit card transactions. A Random Forest Classifier was trained after performing data preprocessing and evaluated using different classification metrics to measure its effectiveness.
