# Financial Stress Testing & Scenario Simulation using Machine Learning

## 📊 Project Overview
This project focuses on **financial stress testing and scenario simulation** using machine learning techniques.  
The objective is to analyze how different **macroeconomic and market risk factors** contribute to financial stress events.

The project demonstrates an **end-to-end machine learning workflow**, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, and feature importance analysis.



## 🧠 Problem Statement
Financial markets are influenced by multiple economic and geopolitical factors.  
This project aims to predict **financial stress events** based on indicators such as:
- Market volatility
- Interest rates
- Inflation
- Liquidity
- Credit spread
- Commodity price changes
- Geopolitical risk


## 📁 Dataset Description
The dataset contains **7,000 observations** and the following features:

| Feature Name | Description |
|--------------|------------|
| Volatility_Index | Market uncertainty indicator |
| Interest_Rate_Pct | Central bank interest rate |
| Inflation_Pct | Inflation rate |
| Liquidity_Ratio | Market liquidity measure |
| Credit_Spread_Pct | Credit risk indicator |
| Commodity_Price_Change_Pct | Commodity market fluctuations |
| Geopolitical_Risk_Index | Global political risk |
| Stress_Event | Target variable (0 = Normal, 1 = Stress) |



## 🔧 Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🔍 Project Workflow
1. Data Loading & Inspection  
2. Data Cleaning & Feature Engineering  
3. Exploratory Data Analysis (EDA)  
4. Feature Selection  
5. Train-Test Split & Scaling  
6. Model Training using Random Forest  
7. Model Evaluation (MSE, R² Score)  
8. Feature Importance Analysis  

---

## 🤖 Machine Learning Model
- **Model Used:** Random Forest  
- **Reason:** Captures non-linear relationships and handles complex interactions between financial variables effectively.

---

## 📈 Model Performance
- **Mean Squared Error (MSE):** Very low  
- **R² Score:** ~0.99  

This indicates strong predictive performance on test data.



## 📌 Key Insights
- Volatility Index, Inflation Rate, Credit Spread, and Geopolitical Risk are the most influential factors.
- Liquidity ratio and commodity price changes have comparatively lower impact.
- The model successfully identifies patterns associated with financial stress events.



