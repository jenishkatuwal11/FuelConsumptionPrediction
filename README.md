# Fuel Consumption Prediction 🚗⛽

This repository contains a complete **end-to-end machine learning project** for predicting vehicle fuel consumption using various regression models. The project includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and comparison of **Linear Regression**, **Decision Tree Regressor**, and **Random Forest Regressor**.

---

## 📁 Dataset

The dataset contains specifications of 970 vehicle models including:

- Engine size
- Transmission type
- Vehicle class
- Number of cylinders
- Fuel type
- CO₂ emissions
- Fuel consumption (target)

📍 **Source**: `fuel-consumption-prediciton.csv`  
📊 **Target Variable**: `Fuel Consumption (L/100 km)`

---

## 🔧 Technologies Used

- **Python**
- **Pandas**, **NumPy**
- **Seaborn**, **Matplotlib**
- **Scikit-learn**
- **Jupyter Notebook**

---

## 📊 Exploratory Data Analysis (EDA)

- Analyzed feature correlations and distributions
- Visualized relationships using bar charts, histograms, heatmaps, and pair plots
- Performed Chi-Square tests to assess categorical feature dependencies
- Detected and removed outliers using IQR method
- Encoded categorical features using:
  - Ordinal Encoding (for ordered categories)
  - One-Hot Encoding (for nominal categories)

---

## 🧪 Machine Learning Models

Three models were trained and evaluated:

| Model             | Training R² | Testing R² | MAE  | RMSE |
| ----------------- | ----------- | ---------- | ---- | ---- |
| Linear Regression | 0.958       | 0.958      | 0.43 | 0.50 |
| Decision Tree     | 0.960       | 0.951      | 0.43 | 0.54 |
| Random Forest     | 0.986       | 0.957      | 0.36 | 0.51 |

📌 **Best Performing Model**: Random Forest Regressor (based on RMSE and MAE)

---

## 📈 Visualizations

- Feature distributions
- Correlation heatmap
- Pair plots
- Model performance bar charts (R² Score & RMSE)
- Decision tree visualization

---

## 🧼 Data Processing Summary

- Removed irrelevant columns like model name, CO2 emissions, and smog rating
- Handled categorical variables using encoding
- Scaled features using `StandardScaler`
- Removed outliers using IQR filtering

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/jenishkatuwal11/FuelConsumptionPrediction.git
   cd FuelConsumptionPrediction
   ```
