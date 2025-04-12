# Crop Yield Prediction Using Machine Learning

Accurate crop yield prediction is critical for efficient resource use and sustainable agriculture. This project leverages machine learning to move beyond traditional farming techniques and help optimize crop production.

---

## Problem Statement

- Lack of **accurate, timely crop yield predictions** leads to inefficient resource use.
- Farmers often rely on **traditional methods**, missing hidden patterns in data.
- This project uses machine learning to:
  - Predict yield before harvesting
  - Identify underperforming regions or crop types
  - Optimize farming decisions using data insights

---

## Dataset Description

- **Source:** [FAOSTAT](https://www.fao.org/faostat/)
- **Columns Used:** Year, Area Harvested, Production, Yield
- **Target Variable:** Yield (tonnes/hectare)
- **Size:** ~10,000+ records

### Data Cleaning

- Removed null values and duplicates
- Focused on major crops: Rice, Wheat, Maize
- Applied label encoding where necessary

---

## Why Machine Learning?

- Traditional models often rely on simple linear assumptions
- ML models like Random Forest can capture complex, non-linear relationships
- Easy to integrate with dashboards and real-time data feeds

### Models Used

- Random Forest
- Linear Regression
- ARIMA (for time-series data)

---

## Model Implementation

**Tools:** Python, Scikit-learn

### Steps

1. Data loading and preprocessing  
2. Feature selection  
3. Train-test split (80/20)  
4. Model training  
5. Model evaluation  
6. Visualization of results  

### Evaluation Metrics

- R² Score
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
