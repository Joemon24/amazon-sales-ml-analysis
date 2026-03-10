# Amazon Sales Machine Learning Analysis

## Project Overview
This project explores whether machine learning models can predict product sales quantity using product price, discount percentage, product category, customer region, and payment method.

The goal was to investigate whether meaningful patterns exist between these features and the number of products sold.

---

## Dataset

The dataset used in this project is publicly available on Kaggle.

Download it here:

https://www.kaggle.com/datasets/aliiihussain/amazon-sales-dataset

The dataset contains **50,000 sales records** with information about product pricing, discounts, categories, customer regions, and payment methods.

---

## Project Workflow

1. Data Inspection  
2. Data Cleaning  
3. Feature Engineering  
4. One-Hot Encoding for categorical variables  
5. Train-Test Split  
6. Model Training  
7. Model Evaluation  
8. Feature Importance Analysis  

---

## Models Used

### Linear Regression
Baseline regression model used to predict `quantity_sold`.

### Random Forest Regressor
Ensemble model used to capture non-linear relationships between features.

---

## Results

Both models produced **very weak predictive performance**:

- Linear Regression → R² ≈ 0  
- Random Forest → R² < 0  

This indicates that the available features do **not contain meaningful predictive information** about the number of items sold.

---

## Key Insight

Exploratory Data Analysis showed that the target variable `quantity_sold` is **almost uniformly distributed** across values.

This means the target behaves almost randomly relative to the available features, making accurate prediction difficult.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Conclusion

This project demonstrates an important machine learning lesson:

**Model performance depends heavily on the quality and relevance of available features.**

Even advanced models cannot perform well if the dataset lacks meaningful predictive relationships.

---

## Author

Joemon
