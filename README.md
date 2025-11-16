# 🧮 Student Performance Prediction (Regression Project)

## 📌 Project Overview
This project aims to **predict a student's Math Score** based on their demographic details, lunch type, parental education, and test preparation status.  
It is a **Regression Machine Learning Project** built using Python, Pandas, and Scikit-Learn.

The goal is to understand which factors influence student performance and build a model that can accurately predict math scores.

---

## 🎯 Problem Statement
Educational institutions want to understand what factors affect students' academic performance.  

The objective of this project is to:
- Analyze the dataset using EDA  
- Find patterns affecting student performance  
- Build a Machine Learning model to **predict Math Scores**  
- Identify the most important features that impact performance  

**ML Type:** Supervised Regression  
**Target Variable:** `math score`

---

## 📂 Dataset Information
Dataset: **Students Performance in Exams**  
Source: Kaggle  
Link: https://www.kaggle.com/datasets/spscientist/students-performance-in-exams  

Rows: 1000  
Columns: 8  

---

## 🧾 Data Dictionary

| Column Name | Type | Description |
|------------|------|-------------|
| gender | Categorical | Gender of the student |
| race/ethnicity | Categorical | Group classification (A to E) |
| parental level of education | Categorical | Parent’s highest education level |
| lunch | Categorical | Lunch type (Standard / Free/Reduced) |
| test preparation course | Categorical | Completed or Not completed |
| math score | Numeric | Math exam score (Target) |
| reading score | Numeric | Reading exam score |
| writing score | Numeric | Writing exam score |

---

## 🛠️ Steps Performed

### 1️⃣ Import Libraries  
Loaded Pandas, Matplotlib, Seaborn, and Scikit-Learn libraries.

### 2️⃣ Load Dataset  
Dataset loaded from Kaggle or local system.

### 3️⃣ Data Understanding  
Checked:
- shape  
- info  
- describe  
- missing values  

### 4️⃣ Exploratory Data Analysis (EDA)  
Plotted:
- distribution plots  
- boxplots  
- correlation heatmap  
- relationship between scores  

### 5️⃣ Data Preprocessing  
- Converted categorical columns using `get_dummies()`  
- Created additional feature `avg_rw` (average of reading & writing)  

### 6️⃣ Train-Test Split  
Split dataset into:
- 80% training  
- 20% testing  

### 7️⃣ Model Building  
Trained the following models:
- Linear Regression  
- Ridge Regression  
- Lasso Regression  
- RandomForestRegressor  
- XGBRegressor  

### 8️⃣ Model Evaluation  
Evaluated using:
- RMSE  
- MAE  
- R² Score  

### 9️⃣ Feature Importance  
Identified which features influenced math scores the most.

### 🔟 Conclusion  
Summarized model performance and key insights.

---

## 🏁 Final Results 
Your results may vary slightly.

| Metric | Value |
|--------|-------|
| RMSE | ~5–10 |
| MAE | ~4–6 |
| R² Score | 0.85+ |

Best-performing model: **RandomForest / XGBoost** (usually)

---

## 🧠 Key Insights 

- Students who **completed test preparation** scored better.  
- Students with **standard lunch** performed better than those with free/reduced lunch.  
- Higher **parental education** → higher math scores.  
- **Reading and writing scores** are strongly related to math performance.

---



