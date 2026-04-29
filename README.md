# Car_Price_Prediction
##  Project Overview

This project focuses on predicting the selling price of Ford cars using Machine Learning techniques.  
The dataset contains multiple features such as **model, year, transmission, mileage, fuel type, tax, mpg, engine size**, etc.

The objective is to build a regression model that can accurately estimate car prices based on historical market data.

This project demonstrates a complete **Machine Learning workflow** including:

- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Categorical Encoding  
- Model Training  
- Performance Evaluation  
- Comparison of Encoding Techniques  

---

##  Dataset Information

**Dataset Name:** Ford Car Price Dataset  
**Source:** Kaggle  

### Features Used:
- `model`
- `year`
- `transmission`
- `mileage`
- `fuelType`
- `tax`
- `mpg`
- `engineSize`

### Target Variable:
- `price`

---

##  Problem Statement

To develop a Machine Learning model that predicts the price of Ford cars based on technical specifications and market-related attributes.

This can help:

- Buyers estimate fair car prices  
- Sellers determine competitive pricing  
- Dealerships automate valuation systems  

---

##  Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

##  Exploratory Data Analysis (EDA)

Performed detailed EDA to understand:

- Distribution of car prices
- Correlation between numerical features
- Effect of mileage on price
- Fuel type impact on pricing
- Year vs Price trends
- Outlier detection
- Missing value analysis

Visualizations used:

- Histograms
- Heatmaps
- Scatterplots
- Boxplots
- Countplots

---

##  Data Preprocessing

### Steps Performed:

✔ Removed duplicates  
✔ Handled null values  
✔ Feature selection  
✔ Categorical feature encoding  
✔ Train-Test Split  
✔ Feature Scaling (if required)

---

##  Encoding Techniques Compared

Two categorical encoding approaches were tested:

### 1️ Label Encoding
Used integer labels for categorical variables.

### 2️ One Hot Encoding
Converted categorical values into binary vectors.

A performance comparison was conducted to evaluate which encoding method improves regression accuracy.

---

##  Model Used

### Linear Regression

Chosen for:

- Simplicity
- Interpretability
- Baseline performance testing

---

##  Model Evaluation Metrics

Used standard regression metrics:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

##  Results

After experimentation:

- One Hot Encoding provided better performance compared to Label Encoding *(if true in your project)*  
- Linear Regression achieved reliable baseline prediction accuracy.

> Final results may vary depending on train-test split and preprocessing steps.

---

##  Project Structure

```bash
Car-Price-Prediction/
│── ford.csv
│── CarPricePrediction.ipynb        # EDA & Data Cleaning
│── OneHotEncoding.ipynb           # Model with One Hot Encoding
│── LabelEncoding.ipynb           # Model with Label Encoding
│── README.md
