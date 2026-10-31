# Weather Trend Forecasting — PM Accelerator Assessment

## Project Overview
This project analyzes weather patterns and develops a machine learning model to estimate future temperatures in Islamabad, Pakistan.

## Dataset
- Source: Global Weather Repository (Kaggle)
- Location selected: Islamabad, Pakistan
- Records used: 876
- Daily temperature observations: 875

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Data cleaning and preprocessing
2. Exploratory Data Analysis (EDA)
3. Temperature and geographical visualizations
4. Anomaly detection
5. Machine learning model comparison
6. Time-series feature engineering
7. Random Forest temperature forecasting
8. Seven-day experimental temperature predictions

## Forecasting Model Results

| Metric | Result |
|---|---:|
| MAE | 1.51°C |
| RMSE | 2.39°C |
| R² Score | 0.716 |

## Forecast Output
The project generated experimental seven-day temperature predictions for Islamabad and saved them in `Islamabad_7_Day_Forecast.csv`.

## Limitations
The predictions are experimental estimates based on the available historical dataset. They are not official weather forecasts. The model's performance on the test period does not guarantee future accuracy.

## Project Files
- `Weather_Trend_Forecasting.ipynb` — Main analysis and forecasting notebook
- `Islamabad_7_Day_Forecast.csv` — Generated forecast results
- `README.md` — Project documentation