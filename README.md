# Interest Rate Prediction using RNN and LSTM

## Introduction
This project focuses on predicting interest rates using deep learning models, specifically Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM) networks. The model is trained on economic indicators such as unemployment rates and Federal Reserve interest rates to capture temporal dependencies and forecast future trends.

## Dataset
The dataset consists of historical economic indicators, including:
- Federal Funds Rate (FEDFUNDS)
- Unemployment Rates
- Other macroeconomic variables impacting interest rate trends

## Why Low Correlation Doesn't Mean Irrelevance
- **Nonlinear Effects:** The relationship between unemployment and FEDFUNDS may be nonlinear and influenced by other variables.
- **Lagged Effects:** Changes in unemployment may impact interest rates with a delay.
- **Deep Learning Strengths:** LSTMs can capture these temporal dependencies effectively.

## Data Preprocessing
- **Scaling:** All features are normalized to the range [0,1] to improve LSTM performance.
- **Sequence Preparation:** Data is structured into input sequences for time-series forecasting.

## Model Implementation
- **LSTM Architecture:** A deep learning model designed to capture long-term dependencies in sequential data.
- **Training:** The model is trained using historical data to predict future interest rates.
- **Evaluation:** Performance metrics such as RMSE and MAE are used to assess accuracy.

## Results & Analysis
- The model successfully captures interest rate trends based on past data.
- Economic insights are derived from model predictions.

## Conclusion
This project demonstrates the effectiveness of deep learning models in financial forecasting. The LSTM model effectively captures economic trends, highlighting the importance of time-series analysis in predicting interest rates.
