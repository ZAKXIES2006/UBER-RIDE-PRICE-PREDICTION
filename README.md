# UBER-RIDE-PRICE-PREDICTION

Predicting NYC Uber fares using machine learning with 200K trip records.

## Results
- Random Forest: R² = 0.826, RMSE = $3.97
- Linear Regression: R² = 0.807, RMSE = $4.17

## Features
- Data cleaning & outlier removal
- Haversine distance calculation from coordinates
- Feature engineering from datetime
- Model comparison (Linear Regression vs Random Forest)
- Interactive Dash dashboard with real-time fare prediction

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly, Dash

## How to Run
1. Clone the repo
2. Install requirements: `pip install -r requirements.txt`
3. Run the notebook: `jupyter notebook UberPricePredictor.ipynb`
