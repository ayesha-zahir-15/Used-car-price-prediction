# House Price Prediction

A machine learning model that predicts house sale prices based on property features, built using linear regression.

## Overview
Buying or selling a home involves estimating a fair price based on dozens of factors — size, location, condition, and more. This project builds a predictive model to estimate house sale prices using the Kaggle House Prices dataset, applying linear regression to uncover which features drive price the most.

## Dataset
- **Source:** Kaggle House Prices dataset
- Contains property-level features such as square footage, number of bedrooms/bathrooms, lot size, year built, and neighborhood, along with final sale price

## Approach
1. **Data Cleaning** — handled missing values, fixed inconsistent data types
2. **Exploratory Data Analysis** — examined feature distributions and correlations with sale price
3. **Feature Engineering** — encoded categorical variables, addressed outliers
4. **Model Training** — fit a linear regression model to predict sale price
5. **Evaluation** — assessed model performance using appropriate regression metrics

## Results
- **R² Score (train set):** 0.64
- **R² Score (test set):** 0.63
- **MSE (test set):** 0.37

The model explains about 63% of the variance in house sale prices on unseen data. 
The close train/test R² scores (0.64 vs 0.63) suggest the model is generalizing reasonably well without significant overfitting.

## Tools Used
Python, pandas, NumPy, scikit-learn, matplotlib/seaborn, Jupyter Notebook

## How to Run
1. Clone this repository
2. Install dependencies: `pip install pandas numpy scikit-learn matplotlib seaborn`
3. Open and run `notebook.ipynb` in Jupyter Notebook

## Files
- `LinearRegression_HousingData.ipynb` — main analysis and model

## Future Improvements
- Try regularized regression (Ridge/Lasso) to handle multicollinearity
- Experiment with tree-based models (Random Forest, XGBoost) for comparison
