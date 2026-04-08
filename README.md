# 🏥 Health Insurance Premium Predictor

A machine learning project that predicts annual health insurance premium amounts based on customer demographics, lifestyle factors, and medical history. Includes an interactive web application for real-time predictions.

![App Screenshot](images/app_screenshot.png)

---

## 📌 Project Overview

Insurance companies rely on accurate premium pricing to remain profitable while staying competitive. This project builds a regression-based ML pipeline that predicts the **Annual Premium Amount** for health insurance customers in India. 

Key insight discovered during analysis: **young customers (age ≤ 25) behave differently** from the rest of the population, leading to a **segmented modelling strategy** — separate models are trained for each group to improve accuracy.


---

## 📊 Dataset

The dataset (`premiums.xlsx`) contains **50,000 records** with multiple features like age, income, BMI, smoking status, and medical history used to predict insurance premiums.

---

## 📊 Exploratory Data Analysis

### 🔥 Correlation Heatmap
![Heatmap](images/heatmap.png)

### 📈 Feature Importance
![Feature Importance](images/feature_importance.png)

### 📉 Data Distribution
![Distribution](images/distribution.png)

---

## 🔍 Methodology

### 1. Exploratory Data Analysis
- Distribution analysis  
- Correlation heatmaps  
- Outlier detection  

### 2. Data Segmentation
- Young Customers (≤ 25)  
- Rest Customers (> 25)  

### 3. Feature Engineering
- Label encoding  
- VIF analysis  
- Feature scaling  

### 4. Model Training
Models evaluated:
- **Linear Regression**
- **Ridge Regression**
- **Lasso Regression**
- **Random Forest Regressor**

---

## 🖥️ Web Application

![App UI](images/app_ui.png)

An interactive **Health Insurance Cost Predictor** app built using **Streamlit**.

### How it Works:
1. User inputs customer details  
2. Model selection based on age segment  
3. Random Forest / Regression model predicts premium  
4. Result displayed instantly  

---

## ⚙️ Tech Stack

| Category | Tools |
|---|---|
| Language | Python 3.10 |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Statistical Analysis | Statsmodels |
| Web App | **Streamlit** |
| Notebook | Jupyter Notebook |

---

## 📈 Results

- Segmented modelling improved accuracy  
- Random Forest outperformed linear models  
- Better predictions for young customers  
- Reduced error using feature engineering  

---

## 🚀 Future Improvements

- Deploy Streamlit app online  
- Add more advanced models (XGBoost, LightGBM)  
- Improve UI/UX  
- Add API integration  

---

## 👤 Author

**Your Name**  
**Gaurav Rajput**
