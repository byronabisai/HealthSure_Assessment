# HealthSure Insurance Cost Analysis

## Overview

This project analyzes the HealthSure medical insurance dataset to identify factors associated with individual medical expenses and develop a machine learning model for predicting insurance costs.

## Objectives

- Explore and understand the dataset
- Identify data quality issues and clean the data
- Perform exploratory data analysis (EDA)
- Analyze relationships between demographic and health-related factors
- Identify key factors influencing medical expenses
- Build and evaluate a machine learning model
- Generate meaningful business insights from the analysis

## Dataset

The dataset contains information about:

- **Age**
- **Sex**
- **BMI**
- **Number of children**
- **Smoking status**
- **Region**
- **Medical expenses**

The dataset initially contained **1,338 records**. After removing one duplicate record, **1,337 observations** remained.

## Analysis

The analysis examines relationships between variables, with particular attention to smoking status, BMI, age, and medical expenses.

One of the key findings was that **smoking status has a strong relationship with medical expenses**, with smokers having substantially higher average expenses than non-smokers.

A strong relationship between BMI and expenses was also observed among smokers, while this relationship was considerably weaker among non-smokers.

## Machine Learning

A **Random Forest Regressor** was developed to predict medical expenses.

### Model Performance

- **R²:** ~0.898
- **MAE:** ~2,464

The model achieved strong predictive performance on the test data, demonstrating that the available demographic and health-related variables contain substantial information for estimating medical expenses.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

```text
HealthSure/
│
├── data/
│   └── healthsure.csv
│
├── notebooks/
│   └── HealthSure_Assessment.ipynb
│
├── README.md
└── requirements.txt
```

## Conclusion

The analysis demonstrates how data science and machine learning can be used to understand healthcare expenditure patterns and predict individual insurance costs. Smoking status, BMI, and other demographic characteristics provide valuable information for explaining differences in medical expenses.

## Author

**Byron Abisai**

