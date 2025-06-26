# Alpha Store – Predictive Forecasting and Inventory Management

## 📌 Project Overview
Alpha Store is a retail chain offering groceries, toys, clothing, electronics, and furniture. This project aims to build and evaluate forecasting models to optimize inventory levels and respond proactively to demand shifts driven by seasonality, promotions, and economic factors.

## 🎯 Objectives
- Develop an effective forecasting system.
- Experiment with multiple forecasting models.
- Identify the most accurate method for demand prediction.
- Improve stock planning and procurement efficiency.

## 📁 Dataset Description
The dataset includes daily records with the following features:
- `Date`
- `Store ID` and `Product ID`
- `Category`, `Region`
- `Inventory Level`, `Units Sold`, `Price`, `Discount`
- `Competitor Price`, `Weather Condition`

## 🧠 Forecasting Techniques Used
- Naïve Forecast
- Moving Average
- Linear Forecast
- Exponential Smoothening
- Simple Linear Regression

## 📊 Results (Evaluation Metrics)

| Method                    | MAD     | MSE        | MPE     |
|--------------------------|---------|------------|---------|
| Naïve                    | 1137.82 | 2,079,918  | 0.0842  |
| Moving Average           | 869.61  | 1,225,229  | 0.0644  |
| Linear Forecast          | 821.21  | 1,062,963  | 0.0609  |
| Exponential Smoothening  | 884.56  | 1,254,651  | 0.0656  |
| Simple Linear Regression | 821.21  | 1,062,963  | 0.0609  |

**✅ Best Performing Model:** Simple Linear Regression – it provides the lowest MAD and MPE, making it the most reliable predictor for demand.

## 🛠️ Tech Stack
- Python (Pandas, NumPy, Matplotlib)
- Excel
- Jupyter Notebooks

## 📌 Insights
- Demand forecasting can reduce overstocking and understocking.
- Historical trends offer valuable guidance for future predictions.
- Linear trends were most consistent across time series evaluation.

## 📤 Contributors
- Amadi Jerry Godspower
