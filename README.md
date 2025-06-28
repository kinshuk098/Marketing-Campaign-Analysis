# Marketing-Campaign-Analysis
# 📈 Marketing Revenue Prediction using Regression

This project uses real-world digital marketing data to predict campaign revenue using machine learning. It includes feature engineering, KPI calculations, and a regression model to forecast outcomes based on ad performance metrics.

---

## 🎯 Goal

To predict marketing campaign revenue using regression analysis and understand the key drivers behind campaign success.

---

## 🔧 Tools Used

- **Python**: pandas, scikit-learn, matplotlib
- **Machine Learning**: Linear Regression
- **Data Cleaning**: Feature extraction from text, handling missing values
- **Visualization**: Actual vs Predicted plots

---

## 📊 Key Steps

### 1. Data Cleaning & KPI Engineering
- Calculated core metrics:
  - **CPA (Cost per Acquisition)**  
  - **ROAS (Return on Ad Spend)**  
  - **CPM (Cost per 1000 Impressions)**  
  - **Revenue per Click**
- Extracted:
  - **Campaign Type**
  - **Device**
  - **Campaign Name**  
  from the Ad Group string using regex

### 2. Predictive Modeling
- Selected features: Impressions, Clicks, Conversions, Cost
- Trained a **Linear Regression** model
- Evaluated using:
  - **R² Score** (Goodness of fit)
  - **RMSE** (Prediction error)

### 3. Visualization
- Plotted **Actual vs Predicted Revenue** to assess model performance

---

## 📌 Outcome

- Achieved high R² score (~0.99), indicating strong predictive ability
- Identified which marketing metrics most influence revenue
- Supports data-driven budget allocation and campaign optimization

---

