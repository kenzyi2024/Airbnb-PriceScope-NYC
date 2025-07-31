# NYCbnb: Predicting Airbnb Listing Prices in New York City

A machine learning project that predicts nightly Airbnb prices using listing attributes like room type, location, review scores, availability, and more. Built with real NYC Airbnb data, this project compares regression models to estimate prices and analyze which features drive value.

## Problem Statement

Given the highly variable pricing of Airbnb listings in NYC, can we build a model that accurately predicts a listing's nightly price based on its characteristics? Accurate predictions can support dynamic pricing tools, outlier detection, and host strategy.

## Results Summary

**Linear Regression**  
- RMSE (log scale): 0.52  
- R² score: 42.4%  
- RMSE (actual price): $124.37

**Random Forest Regressor**  
- RMSE (actual price): $114.66  
- R² score: 30.4%

**Performance Gain**  
- Random Forest reduced RMSE by approximately 8% compared to Linear Regression on actual prices.

## Features Used

- Room Type (one-hot encoded)
- Neighborhood Group
- Superhost Status
- Number of Reviews
- Review Scores (e.g., rating, cleanliness)
- Availability (30–365 day windows)
- Reviews per Month
- Host Listing Count

## Tools and Technologies

- Python (Pandas, NumPy)
- scikit-learn
- Matplotlib and Seaborn for visualization

## Future Work

- Tune model hyperparameters using GridSearchCV
- Try Gradient Boosted Trees (e.g., XGBoost)
- Engineer NLP features from listing descriptions
- Build a front-end interface (e.g., Streamlit) for hosts to get price estimates

## Why This Matters

Airbnb and hosts can use these insights to:
- Set more competitive, data-driven prices
- Detect overpriced or underperforming listings
- Understand which factors most impact pricing

## Contact

Kenzy Ibrahim  
Email: kenzyi2024@gmail.com  
LinkedIn: [linkedin.com/in/kenzyibrahim](https://linkedin.com/in/kenzyibrahim)
