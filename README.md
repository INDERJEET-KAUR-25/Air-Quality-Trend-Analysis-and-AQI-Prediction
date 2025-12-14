# Air Quality Trend Analysis and AQI Prediction Using Machine Learning

## 📌 Project Overview
This project focuses on analyzing **annual air quality data at the U.S. county level** using data science and machine learning techniques.  
The goal is to understand **air pollution trends**, identify **high-risk regions**, detect **extreme pollution events**, and **predict Air Quality Index (AQI)** values using regression and classification models.

The project is developed as part of **CA2 – Skill Based Assessment**, emphasizing real-world, industry-aligned data analytics and ML workflows.

---

## 🎯 Objectives
- Analyze long-term air quality trends across U.S. counties
- Perform data cleaning and preprocessing on real government data
- Conduct Exploratory Data Analysis (EDA) using visualizations
- Compute key statistical measures for air quality assessment
- Predict AQI values using machine learning regression models
- Classify air quality risk levels (Low, Moderate, High)
- Analyze pollutant concentration vs health risk categories
- Detect anomalies and extreme pollution events
- Study year-over-year AQI variability
- Compare pollutant behavior across counties

---

## 📂 Dataset
- **Source:** U.S. Environmental Protection Agency (EPA)
- **Website:** data.gov (government-verified source)
- **Dataset Name:** Annual AQI by County
- **Rows:** < 2000
- **Type:** Structured tabular data (CSV)

### Key Features:
- Year  
- State  
- County  
- Max AQI  
- Median AQI  
- Days Good / Moderate / Unhealthy / Hazardous  

---

## 🛠️ Technologies & Tools
- **Programming Language:** Python  
- **Libraries Used:**
  - pandas, numpy
  - matplotlib, seaborn
  - scikit-learn
- **Environment:** Jupyter Notebook / Python script

---

## 🔍 Project Workflow
1. Load local AQI dataset (CSV)
2. Data cleaning and preprocessing
3. Feature engineering (unhealthy day ratios, totals)
4. Exploratory Data Analysis (EDA)
5. Statistical analysis
6. Regression modeling (AQI prediction)
7. Classification modeling (risk level prediction)
8. Model evaluation
9. Anomaly detection
10. Result interpretation and insights

---

## 📊 Machine Learning Models
### Regression Models
- Linear Regression
- Random Forest Regressor

**Evaluation Metrics:**
- RMSE
- MAE
- R² Score

### Classification Models
- Logistic Regression
- Random Forest Classifier

**Evaluation Metrics:**
- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix

---

## 📈 Key Insights
- Certain counties consistently experience higher AQI levels
- Percentage of unhealthy days strongly correlates with AQI
- Random Forest models outperform linear models
- Extreme pollution events are detectable using statistical thresholds
- Significant year-over-year AQI variability exists across regions

---
