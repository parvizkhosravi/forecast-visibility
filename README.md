# forecast-visibility
# Forecasting Atmospheric Visibility in Tehran's Mehrabad Airport

This project aims to forecast visibility at Tehran's Mehrabad Airport using PM2.5 and relative humidity data with machine learning models.

## Project Structure
forecast-visibility/
├── data/ # Data directory
│ └── Teh_Clean.csv # Original dataset

├── notebooks/ # Jupyter notebooks
│ └── EDA_and_Modeling.ipynb # Exploratory analysis and modeling

├── models/ # Trained models
│ ├── visibility_xgb_model.pkl # Best XGBoost model
│ └── scaler.pkl # Feature scaler

├── app.py # Flask API for deployment

├── requirements.txt # Python dependencies

├── LICENSE # Project license
└── README.md # This file
