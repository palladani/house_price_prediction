# house_price_prediction
Built a production-ready machine learning pipeline for housing price prediction using Scikit-learn with automated preprocessing, model evaluation, and inference.

# 🏠 Housing Price Prediction using Machine Learning

This project implements an **end-to-end machine learning pipeline** to predict house prices based on various housing-related features such as location, median income, population, and number of rooms.

The project is designed following **real-world machine learning best practices**, including data preprocessing, stratified sampling, model training, evaluation, and inference using saved models and pipelines.

---

## 📌 Problem Statement
Predict the **median house value** using housing data by building a robust and reusable machine learning pipeline that can be used for both training and future predictions.

---

## ⚙️ Workflow Overview

1. Load and explore the dataset  
2. Perform **stratified train-test split** based on income categories  
3. Separate features and target variable  
4. Apply preprocessing using pipelines:
   - Handle missing values
   - Scale numerical features
   - Encode categorical features  
5. Train multiple regression models  
6. Evaluate models using cross-validation  
7. Save the best-performing model and preprocessing pipeline  
8. Perform inference on unseen data without retraining  

---

## 🔑 Key Features
- Stratified sampling to preserve income distribution
- Separate pipelines for numerical and categorical features
- Median imputation for missing values
- Feature scaling using `StandardScaler`
- Categorical encoding using `OneHotEncoder`
- Model training using **Random Forest Regressor**
- Model evaluation using **cross-validation**
- Persistent storage of model and pipeline using `joblib`
- Inference pipeline that ensures consistent preprocessing

---

## 🧠 Machine Learning Models Used
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor (Final Model)

---

## 🛠️ Technologies & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib
