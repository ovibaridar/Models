# Models

Machine learning and forecasting models.

## 💊 Pharmaceutical Sales Forecasting
📁 [`Pharmaceutical Sales Forecasting/`](Pharmaceutical%20Sales%20Forecasting)

Forecasts weekly sales of pharmaceutical drug categories (ATC codes such as M01AB, N02BE, R03…) from historical sales data.

| Notebook | Focus |
|---|---|
| `Pharmaceutical Sales Forecasting 1.ipynb` | Data loading, missing values, date handling, XGBoost and neural-network baselines |
| `Pharmaceutical Sales Forecasting  2.ipynb` | Univariate time-series case study: ARIMA / auto-ARIMA, Prophet, statistical models |
| `Pharmaceutical Sales Forecasting  3.ipynb` | Detailed EDA for every drug category and deep-learning (Keras) forecasting |

The dataset is included as `Data Set.zip` ([Pharma sales data on Kaggle](https://www.kaggle.com/datasets/milanzdravkovic/pharma-sales-data)).

**Stack:** pandas · NumPy · scikit-learn · XGBoost · TensorFlow/Keras · statsmodels · Prophet · Plotly · seaborn

## How to run

```bash
git clone https://github.com/ovibaridar/Models.git
cd Models/"Pharmaceutical Sales Forecasting"
unzip "Data Set.zip"
pip install numpy pandas matplotlib seaborn plotly scikit-learn xgboost tensorflow statsmodels prophet
jupyter notebook
```

> Notebook 3 reads the data from a Kaggle path (`/kaggle/input/pharma-sales-data/`). When running locally, change it to the folder where you unzipped the dataset.
