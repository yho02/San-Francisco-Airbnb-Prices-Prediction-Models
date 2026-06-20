# San-Francisco-Airbnb-Prices-Prediction-Models

---

## Description
This project analyzes 10,000+ Airbnb listings in San Francisco (2024–2025) to identify the key factors driving listing prices and build a model that predicts price from listing features. The most influential factors identified were location, property type, and seasonal trends.

## Features

### Feature Engineering
* **Data Cleaning:** Removed missing, invalid, and fake/duplicate listings that were skewing price predictions
* **New Features:**  Engineered geographic features, including distance to the closest BART station or major attractions.
* **Outlier Removal:** Excluded outliers that skewed property prices to ensure model accuracy.

### Predictive Models
We implemented and compared the following models:
* Linear Regression (baseline)
* CART
* Random Forest
* Gradient Boosting

### Results 
The best-performing model is Gradient Boosting, which achieved an **R² of 0.85**, outperforming the linear regression baseline by **70%**.

## Data Source
The data for this project is sourced from [Inside Airbnb](https://insideairbnb.com/).
