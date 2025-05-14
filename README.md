# 🚢 Titanic EDA Analysis 🔍

![Python](https://img.shields.io/badge/Built%20With-Python-blue?style=for-the-badge&logo=python)
![EDA](https://img.shields.io/badge/Project-Type%3A%20EDA-lightgrey?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Tool-Jupyter%20Notebook-orange?style=for-the-badge&logo=jupyter)

## 📌 Overview

This project performs **Exploratory Data Analysis (EDA)** on the **Titanic dataset**, a classic dataset used for data science and machine learning practice. The goal is to uncover hidden patterns, understand the structure of the data, and extract insights that could help in predictive modeling (like survival prediction).

---

## 🎯 Project Objective

> To explore, summarize, and visualize key characteristics of the Titanic dataset using Python and derive actionable insights that support further machine learning modeling.

---

## ⚙️ Tools & Libraries Used

- 📒 Jupyter Notebook  
- 🐍 Python  
- 📊 Pandas, NumPy  
- 📈 Matplotlib, Seaborn  

---

## 🔍 Key Steps Performed

1. **Dataset Used**: [Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)
2. **Data Loading**: Loaded the dataset using `pandas`.
3. **Initial Exploration**:
   - Checked data types, null values, and dataset structure.
   - Displayed summary statistics using `.describe()` and `.info()`.
4. **Data Cleaning**:
   - Handled missing values (e.g., Age, Embarked).
   - Dropped irrelevant columns like PassengerId or Ticket.
5. **Univariate Analysis**:
   - Analyzed survival counts, gender distribution, fare ranges, etc.
6. **Bivariate & Multivariate Analysis**:
   - Correlated features like Pclass vs Survival, Age vs Survival.
   - Used heatmaps, bar plots, and violin plots for visual interpretation.
7. **Insights Extraction**:
   - Noted which features could impact survival probability (e.g., Gender, Class).

---

## 📋 Insights Gained

- **Females and 1st class passengers** had higher survival rates.
- **Children under age 10** had a better chance of survival.
- **Missing data** in Age and Embarked required imputation for model use.
- **Fare and Class** showed strong correlation with survival.
- Class imbalance observed in Survival values (more passengers died than survived).

---  

---

