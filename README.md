# WHO Life Expectancy – CIND820 Final Project

This repository contains all code, documentation, and files used for my CIND820 Capstone Project at Toronto Metropolitan University.  
The goal of the project is to analyze global WHO indicators and build machine learning models to predict life expectancy across countries.
---

## 🔍 Project Overview

This project explores the key factors that influence life expectancy and evaluates different machine learning models for prediction, including:

- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  

The Random Forest model achieved the best performance with a test R² of **0.958** and strong stability across cross-validation folds.

---

## 🧠 Key Objectives

- Identify the most important predictors of life expectancy  
- Compare multiple machine learning models  
- Evaluate models based on effectiveness, efficiency, and stability  
- Provide reproducible analysis with clear documentation  

---

## 🔁 Reproducibility Instructions

To reproduce the results:

1. Open the notebook file below in Google Colab:  
   `notebook/Patel_Himit_InitialResults.ipynb`

2. Upload the dataset when prompted (if not included).

3. Run all cells from top to bottom.

4. The notebook will automatically:
   - Clean and preprocess the data  
   - Generate all visualizations (correlation heatmap, feature importance, etc.)  
   - Train and evaluate all models  
   - Produce the comparison table and final analysis  

All results (accuracy metrics, cross-validation scores, and plots) will be generated automatically.

---

## 📊 Final Results Summary

- **Best Model:** Random Forest  
- **Test R²:** 0.958  
- **MAE:** ~1.22 years  
- **RMSE:** ~1.90 years  
- **Most Important Features:** Adult Mortality, Schooling  

---

## 📚 Data Source

World Health Organization (WHO).  
Global Health Observatory (GHO) data.  
https://www.who.int/data/gho

---

## 👤 Student Information

- **Name:** Himit Patel  
- **Course:** CIND820 – Capstone Project  
- **Program:** Big Data & Analytics  
- **Supervisor:** Dr. Ceni Babaoglu  
- **University:** Toronto Metropolitan University  
- **Year:** 2025  
