# 🏠 Housing Price Prediction using Machine Learning

This project implements an **end-to-end machine learning pipeline** to predict house prices based on various housing-related features such as location, median income, population, and number of rooms.

The project follows **real-world machine learning best practices**, including data preprocessing, stratified sampling, model training, evaluation, and inference using reusable pipelines.

---

## 📌 Problem Statement
Predict the **median house value** using housing data by building a robust, reusable, and production-ready machine learning pipeline that can be used for both training and future predictions.

---

## ⚙️ Workflow Overview
- Load and explore the dataset  
- Perform **stratified train-test split** based on income categories  
- Separate features and target variable  
- Apply preprocessing using pipelines:
  - Handle missing values using median imputation  
  - Scale numerical features using `StandardScaler`  
  - Encode categorical features using `OneHotEncoder`  
- Train multiple regression models  
- Evaluate models using **cross-validation**  
- Save the best-performing model and preprocessing pipeline  
- Perform inference on unseen data without retraining  

---

## 🔑 Key Features
- Stratified sampling to preserve income distribution
- Separate pipelines for numerical and categorical features
- Median imputation for missing values
- Feature scaling using `StandardScaler`
- Categorical encoding using `OneHotEncoder`
- Model training using **Random Forest Regressor**
- Model evaluation using cross-validation
- Persistent storage of model and pipeline using `joblib`
- Inference pipeline that ensures consistent preprocessing

---

## 🧠 Machine Learning Models Used
- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor *(Final Model)*  

---

## 🛠️ Technologies & Libraries
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Joblib  

---

## 📌 Notes
Trained models are **not committed to the repository** to keep it lightweight and clean.  
Models are generated locally during execution using the same training pipeline.

---

## 🎯 Why This Project?
This project demonstrates how to design a **production-ready machine learning system**, ensuring consistency between training and inference while following industry-standard practices.
