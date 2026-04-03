# energy-forecasting
Energy forecasting system using CNN-LSTM models for short-term and LSTM-based deep learning for long-term prediction of solar irradiance (GHI) using time-series data.


This project implements short-term and long-term energy forecasting using deep learning models on time-series data, specifically targeting Global Horizontal Irradiance (GHI) prediction.

The short-term forecasting model uses a CNN-LSTM architecture to capture both local patterns and temporal dependencies for high-resolution predictions.
The long-term forecasting model uses an LSTM-based approach to learn long-term trends and seasonality in the data.
The system is trained on historical energy data and evaluated using standard regression metrics.


Key Features
CNN-LSTM hybrid model for short-term forecasting
LSTM-based model for long-term forecasting
Time-series preprocessing (interpolation, scaling, windowing)
Sliding window approach for sequence generation
Model evaluation using RMSE, MSE, MAE, and R² score


Technical Highlights
Sequence length (windowing) used for temporal learning
Data normalization using MinMaxScaler
Early stopping to prevent overfitting
Forecast vs actual visualization for performance analysis
Use Cases


Solar energy generation prediction
Smart grid optimization
Renewable energy planning
