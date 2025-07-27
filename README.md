# 🚚 Route Rate Prediction Project

This project involves analyzing and predicting transportation rates between origin and destination cities using machine learning and data visualization techniques.

---

## ✅ Problem Statement
"Freight and logistics companies often struggle to predict transportation rates accurately due to dynamic factors like route distance, location demand, 
and market fluctuations. This project aims to develop a machine learning model that can predict route-based freight rates based on historical data of origin, 
destination, miles, duration, and other logistics variables. Additionally, an interactive Power BI dashboard is built to help stakeholders visualize trends, 
identify profitable routes, and make data-driven pricing decisions."

---

## 🧾 Contents

- **Raw Data**: route-level rate information (origin, destination, miles, rate, etc.)
- **Transformed Data**: cleaned and engineered dataset
- **ML Notebook**: end-to-end model pipeline to predict rates
- **Power BI Dashboard**: visual insights for business decisions

---

## 🔄 Methodology

The project follows a structured data science and analytics workflow combining machine learning and business intelligence:

### 1. 📥 Data Collection & Understanding
- Imported raw route-based freight rate data containing features like origin, destination, miles, rate, duration, etc.

### 2. 🧹 Data Preprocessing
- Treated missing values, incorrect formats, and outliers
- Performed data transformations and feature engineering (e.g., converting ZIP codes, calculating rate per mile)

### 3. 📊 Exploratory Data Analysis (EDA)
- Visualized patterns in average rates by city/state
- Identified key factors affecting rate variability
- Used correlation analysis and distribution plots

### 4. 🧠 Machine Learning Modeling
- Applied regression algorithms such as:
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting Regressor
- Evaluated using metrics: RMSE, MAE, R² Score

### 5. 📈 Model Evaluation
- Compared model performance using:
  - Cross-validation scores
  - Residual error plots
  - Feature importance analysis

### 6. 📊 Power BI Visualization
- Created an interactive dashboard showing:
  - Average rates by origin/destination
  - Filters for city, state, equipment type
  - Route-based performance metrics

---

## 📊 Power BI Dashboard

📁 `dashboard/Route_Based_Rate_Forecasting_Dashboard.pbix`

The dashboard includes:
- Top origin & destination cities
- Average and max rates by route
- Rate variation across states
- Filters for state, equipment type, and duration

---

## 📈 Machine Learning Pipeline

📁 `notebooks/Rate_Prediction_using_ML.ipynb`

Steps:
1. Data preprocessing
2. Feature engineering
3. Model building using regression algorithms
4. Evaluation with RMSE, MAE

---

## 📁 Dataset

📁 `data/`
- `rate_based_on_origin_and_destination.csv`: Original raw data
- `rate_based_on_origin_and_destination_transformed.csv`: Cleaned & processed

---

## 🧰 Tools Used

- Python (Pandas, NumPy, Matplotlib.pyplot, Seaborn, Scikit-learn)
- Power BI
- Jupyter Notebook
