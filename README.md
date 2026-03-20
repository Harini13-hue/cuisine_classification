# 🍜 Cuisine Classification Model

A machine learning model to classify restaurants by cuisine type
using Random Forest and Logistic Regression on the Zomato dataset.

## 📊 Results
- **Best Model:** Random Forest Classifier
- **Overall Accuracy:** 45%
- **Best Recall:** North Indian (77%)
- **Key Finding:** Class imbalance causes bias toward North Indian cuisine

## 🔍 Bias Analysis
- South Indian: 0% recall due to only 57 training samples
- Location (Longitude/Latitude) accounts for 45.8% of feature importance
- Chinese restaurants confused with North Indian 105 times

## 🛠️ Tech Stack
Python | Pandas | Scikit-learn | Random Forest | Seaborn | HTML | Chart.js

## 📁 Files
- `cuisine_classification.ipynb` — Full ML pipeline
- `cuisine_dashboard.html` — Interactive results dashboard
- `Dataset .csv` — Zomato restaurant dataset

## 🔗 Live Dashboard
[View Dashboard](https://Harini13-hue.github.io/cuisine-classification/cuisine_dashboard.html)
