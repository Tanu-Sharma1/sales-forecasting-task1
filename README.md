# Sales Forecasting Project (Walmart Dataset)

## Project Overview
This project focuses on forecasting weekly sales using historical retail data. The goal is to analyze sales patterns and build a machine learning model that can predict future sales with high accuracy.
--
## Dataset Description
The project uses multiple datasets:
- 'train.csv' – Historical sales data
- 'test.csv' – Test dataset for prediction
- 'features.csv' – Additional store features
- 'stores.csv' – Store-related information
---
## Workflow

### 1. Data Preprocessing
- Converted date columns into datetime format
- Handled missing values by filling with 0
- Checked and handled duplicate data

### 2. Feature Engineering
- Extracted:
  - Year
  - Month
  - Week number
- Applied One-Hot Encoding on categorical variable `Type`

### 3. Data Merging
- Merged train dataset with features and store information using Store and Date columns

### 4. Exploratory Data Analysis (EDA)
- Sales trend over time
- Monthly sales distribution
- Holiday vs non-holiday sales comparison
- Correlation heatmap

### 5. Model Building
- Split dataset into training and testing sets
- Trained a regression model on sampled data (50,000 rows)

### 6. Model Evaluation
- Mean Absolute Error (MAE)
- R² Score
---

## Results
- MAE: ~1454
- R² Score: ~0.97

---

## Visualizations
- Sales trend over time
- Monthly sales analysis
- Holiday impact on sales
- Correlation heatmap
- Actual vs Predicted sales

---
## Libraries Used
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---
## Conclusion
This project demonstrates how machine learning can be used for retail sales forecasting with strong predictive performance.

---

## Author
Tanu Sharma
