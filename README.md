# Daecheong Dam Water Level Prediction

LSTM-based water level prediction model for Daecheong Dam using hourly meteorological and upstream hydrological data.

## Model

- PyTorch
- 2-layer LSTM
- Optuna hyperparameter tuning
- Target: Daecheong Dam water level

## Data

Input data includes rainfall, humidity, temperature, pressure, upstream water levels, Yongdam Dam water level, and past Daecheong Dam water level.

## Evaluation

Metrics: NSE, KGE, RMSE, MAE

## Uncertainty Estimation

This project includes predictive uncertainty estimation using conformal prediction to support more reliable flood and dam operation decisions.

## Note

Data, trained weights, scaler files, and outputs are not included.