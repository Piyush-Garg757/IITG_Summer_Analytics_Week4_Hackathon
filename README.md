# IITG Summer Analytics Week 4 Hackathon 🚀

This repository contains my solution for the **Week 4 Hackathon** organized as part of the IIT Guwahati Summer Analytics Program. The challenge focuses on developing a predictive model for identifying individuals with a higher risk of heart disease based on the **NHANES (National Health and Nutrition Examination Survey)** dataset.

---

## 📊 Problem Statement

Given various demographic, lifestyle, and medical attributes, the task is to predict whether an individual has **heart disease**. This is framed as a **binary classification** problem.

---

## 📁 Dataset

The dataset is sourced from the **NHANES** public health survey and includes features such as:

- Age
- Gender
- BMI
- Blood Pressure
- Cholesterol levels
- Smoking and alcohol usage
- Physical activity
- Medical history

The target variable is:
- `heart_disease`: `1` indicates presence, `0` indicates absence.

---

## 🧠 Approach

### 🔍 Data Preprocessing
- Handled missing values via imputation
- Encoded categorical variables
- Performed feature scaling
- Engineered new features for better separability

### ⚙️ Model Training
- Baseline models: Logistic Regression, Decision Trees
- Final model: **XGBoost Classifier**
- Used **GridSearchCV** for hyperparameter tuning

### 📈 Evaluation
- Accuracy
- Precision, Recall, F1-score
- ROC-AUC curve
