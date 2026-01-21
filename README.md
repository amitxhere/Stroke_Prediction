# 🧠 Stroke Prediction Using Machine Learning

This project implements multiple machine learning algorithms to predict the likelihood of stroke occurrence in patients based on various health indicators and demographic information. The goal is to identify high-risk individuals and potentially aid in early intervention.

---

## 📖 Project Story

Stroke is one of the leading causes of death and long-term disability worldwide. Early detection plays a critical role in reducing severe health complications and improving patient outcomes. However, identifying high-risk individuals manually can be time-consuming and prone to human error.

In this project, I developed a machine learning-based predictive system that analyzes patient health records and demographic information to estimate the probability of stroke occurrence. The dataset consists of 5,110 patient records containing attributes such as age, glucose level, BMI, hypertension status, heart disease history, work type, residence type, and smoking behavior.

One of the major challenges in this dataset was class imbalance, where only about 4.9% of patients had experienced a stroke. Additionally, the BMI column contained missing values, which were handled using mean imputation. Categorical features were encoded using label encoding, and numerical features were scaled using StandardScaler to improve model performance.

Multiple machine learning models were trained and compared, including Logistic Regression, Support Vector Machine (SVM), Random Forest, and Gradient Boosting. Among these models, Gradient Boosting achieved the best performance with an accuracy of 94.62%, demonstrating strong predictive capability in identifying high-risk patients.

This project demonstrates an end-to-end machine learning workflow — from raw data preprocessing to model evaluation — and highlights how data-driven solutions can support early medical intervention and decision-making.

---

## 📊 Dataset

The dataset contains **5,110 patient records** with the following features:

### 🔹 Features

- **id**: Unique patient identifier  
- **gender**: Patient's gender (Male / Female / Other)  
- **age**: Patient's age  
- **hypertension**: Hypertension status (0 = No, 1 = Yes)  
- **heart_disease**: Heart disease status (0 = No, 1 = Yes)  
- **ever_married**: Marital status (Yes / No)  
- **work_type**: Type of occupation (Private, Self-employed, Government, etc.)  
- **Residence_type**: Residence area (Urban / Rural)  
- **avg_glucose_level**: Average glucose level in blood  
- **bmi**: Body Mass Index  
- **smoking_status**: Smoking status (formerly smoked, never smoked, smokes, Unknown)  
- **stroke**: Target variable (0 = No stroke, 1 = Stroke)  

---

### 📌 Data Statistics

- **Total records**: 5,110  
- **Missing values**: 201 values in BMI column (handled using mean imputation)  
- **Class imbalance**: Approximately **4.9% stroke cases**

---

## 🔧 Features Implemented

- Data preprocessing and cleaning  
- Handling missing values (BMI imputation)  
- Label encoding for categorical variables  
- Feature scaling using **StandardScaler**  
- Implementation of multiple machine learning algorithms  
- Model evaluation using **Accuracy** and **ROC-AUC**  
- Class imbalance handling using **balanced class weights**

---

## 🤖 Models Implemented

### 1️⃣ Logistic Regression
- **Accuracy**: 74.66%  
- **ROC-AUC**: 83.66%  

---

### 2️⃣ Support Vector Machine (SVM)
- **Accuracy**: 76.22%  
  

---

### 3️⃣ Random Forest Classifier
- **Accuracy**: 92.66%  
  
