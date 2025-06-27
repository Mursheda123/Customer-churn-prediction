# Customer-churn-prediction

# 🧠 Customer Churn Prediction Project

Predicting customer churn using various classification models to support proactive retention strategies.

---

## 📌 Project Overview

This project focuses on building machine learning models to predict whether a customer is likely to **churn** (leave the service). We use a cleaned dataset with demographic and financial variables and apply several supervised learning algorithms to identify patterns of churn.

---

## 📂 Dataset

The dataset contains customer information such as:
- **Geography**, **Gender**, **Age**, **Tenure**
- **Balance**, **Estimated Salary**, **Credit Score**
- Target column: `Exited` (1 = churned, 0 = retained)

---

## 🔧 Preprocessing Steps

- Removed duplicates and missing values.
- Applied **label encoding** and **one-hot encoding**.
- Performed **train-test split with stratification**.
- Balanced the dataset using **SMOTEENN** to address class imbalance.

---

## 🧪 Models Use

| ✅ Random Forest      
| Decision Tree         
| XGBoost               
| Neural Network (MLP) 
| Logistic Regression   
| Naive Bayes           
| SVC                   
| K-Nearest Neighbors 

---

## 📈 ROC Curve

The ROC curve shows the model’s performance across all classification thresholds. AUC score closer to 1 indicates better separation of churn vs. non-churn.

### 🔹 Final Random Forest Model (after SMOTEENN)

- **Accuracy:** 0.76%
- **ROC AUC:** 0.86
- **F1 Score:** 0.80

### 📊 ROC Curve Plot:
![ROC Curve](roc_curve.png)

---

## 🧪 Confusion Matrix (Random Forest)
[[304 161]
 [ 83 478]]

