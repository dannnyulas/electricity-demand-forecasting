# Electricity Demand Forecasting

University machine learning project developing a deep learning pipeline for 24-hour electricity demand forecasting.

## Project Overview

The system uses historical electricity load, temperature and calendar information to predict the following 24 hours of electricity demand.

## Key Features

• Time-series data preprocessing
• Cyclical calendar feature engineering
• Sequential train, validation and test splitting
• Train-only normalisation
• 168-hour historical input window
• 24-hour multi-step forecasting
• PyTorch 1D CNN
• Batch normalisation and dropout
• Early stopping
• RMSE and MAE evaluation

## Results

The final model reduced forecasting error by more than 60% compared with the provided benchmark and outperformed the benchmark on 6 of the 7 test days.

## Tools

Python, PyTorch, Pandas, NumPy, Scikit-learn, Matplotlib
