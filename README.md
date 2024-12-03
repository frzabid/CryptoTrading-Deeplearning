# BTC Trading Bot using LSTM

This repository contains a Python-based project that implements a **Bitcoin (BTC) Trading Bot** using **Long Short-Term Memory (LSTM)** models. The notebook demonstrates a step-by-step approach to predicting Bitcoin price movements and automating trades based on predictive analytics.

## File Description

### `Trading bot BTC LSTM.ipynb`
This Jupyter Notebook includes:
- **Data Preparation**: Data loading, cleaning, and feature engineering.
- **Model Development**: Implementation of an LSTM model to predict future Bitcoin prices based on historical data.
- **Trading Strategy**: A trading bot that uses the model's predictions to execute buy/sell signals.
- **Evaluation**: Performance metrics and visualization of trading results.

### `actual vs predicted.png`
This visualization shows the comparison between the **Actual Prices** and **Predicted Prices** generated by the LSTM model. Key performance metrics:
- **Mean Absolute Error (MAE)**: 0.0395
- **Mean Squared Error (MSE)**: 0.0022
- **Root Mean Squared Error (RMSE)**: 0.0468

![Actual vs Predicted Prices]
![Actual vs Predicted Prices](actual_vs_predicted.png)

## Prerequisites
- Python 3.8+
- Libraries: `numpy`, `pandas`, `tensorflow`, `sklearn`, `matplotlib`, `seaborn`

## Usage
1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook and run it:
   ```bash
   jupyter notebook Trading\ bot\ BTC\ LSTM.ipynb
   ```

## Features
- Predictive analysis of Bitcoin prices using LSTM.
- Implementation of a trading bot with customizable strategies.
- Comprehensive visualizations for better insights into model performance and trading outcomes.

## Contributing
Feel free to submit issues or pull requests to improve the project.
