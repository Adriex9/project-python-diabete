# 🩺 U.S. Diabetes Prediction – Data Cleaning & ML Modeling

This project focuses on preparing and modeling a real-world dataset of diabetes-related hospitalizations in the U.S. The dataset required significant preprocessing before applying machine learning techniques. The goal was to predict patient outcomes based on medical records and demographic data.

---

## 📚 Context

This project was completed as part of my studies at **ESILV (École Supérieure d'Ingénieurs Léonard-de-Vinci)**. The dataset contains anonymized information about patients diagnosed with diabetes and their hospital stays across the U.S.

---

## 🧹 Data Cleaning & Preprocessing

The original dataset contained noisy and inconsistent entries. Key steps in preprocessing included:

- Handling missing values and placeholder codes (e.g., `?`, `NaN`)
- Removing irrelevant or redundant columns
- Encoding categorical variables
- Balancing the dataset for fair classification
- Scaling numerical features

These steps were crucial to ensure compatibility with machine learning models and improve predictive performance.

---

## 🤖 Machine Learning Models

Two classification algorithms were used to model the dataset:

### ✅ Random Forest
- Accuracy: **0.830**
- Benefits: Handles categorical data well, robust to overfitting

### ✅ Support Vector Machine (SVM)
- Accuracy: **0.829**
- Benefits: Effective in high-dimensional spaces, good generalization

---

## 🧪 Goal

The primary objective was to predict whether a diabetic patient would be readmitted to the hospital within 30 days.

---

## 📂 Project Structure

