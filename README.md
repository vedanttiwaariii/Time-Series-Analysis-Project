Overview
This project focuses on predicting electricity demand across multiple zones using historical power consumption data. The aim is to enable accurate short-term and long-term forecasting to support effective power grid management and resource planning.

Goals
Forecast electricity demand with high accuracy.

Compare the performance of traditional statistical models and advanced deep learning models.

Provide a scalable and reproducible forecasting framework.

Process
Data Collection & Cleaning – Imported historical consumption datasets, handled missing values, and normalized features.

Exploratory Data Analysis (EDA) – Visualized trends, seasonality, and correlations.

Stationarity Testing – Applied ADF and KPSS tests to check for unit roots and stationarity.

Feature Engineering – Created lag features, rolling means, and encoded time-based variables.

Model Development – Implemented ARIMA, LSTM, GRU, Prophet, and RNN models.

Model Evaluation – Compared results using MAE, RMSE, and R² scores.

Optimization & Tuning – Fine-tuned hyperparameters to maximize accuracy.

Features
Multi-model comparison between statistical and deep learning methods.

Feature-rich preprocessing pipeline for time series datasets.

Evaluation framework to ensure reproducibility and fairness in model comparisons.

Support for both short-term and long-term forecasting horizons.

Results
ARIMA performed well for stable trends with minimal seasonality.

LSTM and GRU outperformed traditional methods for complex, seasonal patterns.

Prophet provided competitive results with easier interpretability.

Skills Used
Time Series Analysis

ARIMA Modeling

LSTM, GRU, RNN

Prophet Forecasting

Feature Engineering

Model Evaluation (MAE, RMSE, R²)
