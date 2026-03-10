# Amazon Sales Machine Learning Analysis

## Project Overview
This project investigates whether machine learning models can predict product sales quantity using product price, discount, ratings, and customer attributes.

## Dataset
Amazon Sales Dataset containing 50,000 records with product, pricing, and customer information.

## Methods
- Data Cleaning
- Feature Engineering
- One-Hot Encoding
- Train-Test Split
- Linear Regression
- Random Forest
- Feature Importance Analysis

## Results
Both models produced very weak predictive performance (R² ≈ 0), indicating that the dataset lacks strong predictive relationships between the available features and the target variable.

## Key Insight
Exploratory data analysis showed that `quantity_sold` is almost uniformly distributed, meaning the target variable behaves randomly relative to the features.
