# AI/ML Engineering Internship Tasks  
**Submitted by: Naima Imtiaz**  
DevelopersHub Corporation  

This repository contains three completed tasks as part of the AI/ML Engineering Internship program.  
The projects focus on data exploration, regression modeling, and classification in real-world scenarios.

---

# Task 1: Exploring and Visualizing the Iris Dataset

## Objective
To understand how to load, inspect, summarize, and visualize a dataset in order to identify patterns, distributions, and relationships between features.

## Dataset
Iris Dataset (loaded using pandas from a public CSV source)

## Key Steps Performed
- Loaded dataset using pandas
- Inspected dataset structure using `.shape()`, `.info()`, `.describe()`
- Checked column names and previewed sample rows
- Created:
  - Scatter plot (feature relationships)
  - Histograms (distribution of values)
  - Box plots (outlier detection)

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn

## Key Insights
- Different iris species show distinct clustering patterns.
- Petal measurements are more separable than sepal measurements.
- Some features contain mild outliers.

---

# Task 2: Short-Term Stock Price Prediction (Tesla - TSLA)

## Objective
To predict the next day’s closing stock price using historical data and regression models.

## Dataset
Tesla (TSLA) historical stock data retrieved using `yfinance`.

## Features Used
- Open
- High
- Low
- Volume

Target:
- Next day Close price (shifted by one day)

## Models Implemented
- Linear Regression
- Random Forest Regressor

## Evaluation Metrics
- Mean Absolute Error (MAE)
- R² Score
- Actual vs Predicted Price Visualization

## Tools Used
- Python
- yfinance API
- Pandas
- Scikit-learn
- Matplotlib

## Key Insights
- Random Forest generally performs better than Linear Regression.
- Tree-based models capture nonlinear patterns in stock movement more effectively.
- Time-based data splitting is crucial to prevent data leakage.

---

# Task 3: Heart Disease Prediction

## Objective
To build classification models that predict whether a patient is at risk of heart disease based on medical attributes.

## Dataset
Heart Disease UCI Dataset

## Key Steps Performed
- Data cleaning and missing value handling
- Exploratory Data Analysis (EDA)
- Correlation heatmap
- Distribution and relationship visualizations
- Feature scaling (StandardScaler)
- Train-test split with stratification

## Models Implemented
- Logistic Regression
- Decision Tree Classifier

## Evaluation Metrics
- Accuracy
- ROC-AUC Score
- Confusion Matrix
- Classification Report
- ROC Curve
- Feature Importance Analysis

## Tools Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

## Key Insights
- Logistic Regression showed strong generalization ability.
- Decision Tree highlighted key predictive features.
- Chest pain type and maximum heart rate were among the most influential predictors.
- ROC-AUC above 0.85 indicates reliable classification performance.
---

# Overall Skills Demonstrated

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Regression modeling
- Binary classification
- Model evaluation using multiple metrics
- Visualization and interpretation of results
- Feature importance analysis
- API-based data fetching
- Time-series aware data splitting

---

# Conclusion

These tasks demonstrate practical implementation of machine learning workflows including data exploration, predictive modeling, evaluation, and visualization. The projects reflect foundational AI/ML engineering skills required for real-world applications.
---

# Repository Structure
