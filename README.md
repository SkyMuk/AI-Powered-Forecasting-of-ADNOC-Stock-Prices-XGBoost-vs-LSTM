
# XGBoost vs LSTM on ADNOC Financial Time Series Data

This project compares two powerful modeling techniques, **XGBoost** and **LSTM**, on ADNOC-related financial time series data to forecast trends, evaluate performance, and extract actionable insights.

## Project Structure

- `notebooks/`: Contains the main Jupyter notebook with model implementation and evaluation
- `data/`: Placeholder for input data files (CSV format)
- `plots/`: Visualizations comparing model predictions
- `models/`: Saved model files (e.g., XGBoost `.pkl`, LSTM `.h5`)

## Models Compared

### 1. XGBoost
A gradient boosting model optimized for tabular data. Strong performance with explainability via SHAP.

### 2. LSTM (Long Short-Term Memory)
A recurrent neural network model specialized in sequential time series forecasting.

## Key Features

- Data normalization and preprocessing
- Model training and evaluation (RMSE, MAE, R², MAPE)
- Visual comparison of actual vs predicted results
- Feature importance with SHAP for XGBoost
- Final recommendation based on model performance

## How to Use

1. Place your time series CSV file in the `data/` directory.
2. Run the notebook in `notebooks/` to preprocess data and train models.
3. Review the output plots and metrics.
4. Modify or extend the architecture for experimentation.

## Use Cases

- ADNOC cost forecasting
- Oil sector financial trend prediction
- Energy demand modeling
- Trading signal analysis

## Requirements

Install required Python packages:

```bash
pip install -r requirements.txt
```

## License

This project is intended for educational and demonstration purposes.
