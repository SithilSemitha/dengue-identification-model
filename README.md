# Dengue Identification Model

A simple supervised machine learning project for predicting dengue cases using historical data and relevant environmental features.

## Project Overview
This project builds a supervised regression model to estimate dengue case counts based on input features such as weather-related variables. The model is trained on labeled data and evaluated using common regression metrics.

## Dataset
- Dataset file: final.csv
- Target variable: cases
- Features: numeric input variables used for prediction

## Model
- Algorithm: RandomForestRegressor
- Preprocessing: feature scaling with StandardScaler
- Split strategy: 80% training and 20% testing

## Files
- dengue.py: training, evaluation, and prediction script
- Dengue.ipynb: notebook version of the workflow
- final.csv: dataset used for model training

## How to Run
1. Install the required Python libraries:
   - pandas
   - numpy
   - scikit-learn
   - matplotlib
   - seaborn
2. Run the script:
   python dengue.py

## Evaluation Metrics
The model performance is measured using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R-squared (R2)
