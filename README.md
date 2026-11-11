# Renewable Energy Output Prediction Using PySpark

## Project Overview

This project focuses on predicting renewable energy AC power output using weather and environmental parameters. It uses PySpark-based Linear Regression for prediction and Power BI for interactive data visualization and performance analysis.

## Project Details

- **Domain:** Renewable Energy & Machine Learning
- **Big Data Technology:** Apache PySpark
- **Machine Learning Algorithm:** Linear Regression
- **Visualization Tool:** Microsoft Power BI
- **Dataset Size:** 2,777 records
- **Features:** Solar radiation, temperature, relative humidity, wind speed, wind direction, and solar angles.

## Data Processing

- Cleaned and preprocessed the dataset.
- Handled invalid relative humidity values.
- Performed feature engineering.
- Divided the dataset into training and testing sets.
- Training records: 2,221
- Testing records: 556

## Model Performance

The Linear Regression model was evaluated using three standard regression metrics.

| Metric | Result |
|---|---:|
| R² Score | 78.76% |
| RMSE | 175.82 |
| MAE | 140.26 |

## Power BI Dashboard

The project includes a three-page interactive dashboard.

### 1. Main Dashboard
- Total, training, and testing records.
- Actual vs. predicted AC output.
- Monthly energy output.
- Hourly energy generation.
- Temperature and AC output relationship.

### 2. ML Model Analysis
- Model performance indicators.
- Actual vs. predicted output comparison.
- Prediction error analysis.
- Training vs. testing error comparison.
- Prediction error distribution.

### 3. Weather Analysis
- Solar radiation analysis.
- Temperature heatmap by month and hour.
- Relative humidity analysis.
- Wind speed analysis.
- Weather conditions and AC output relationship.

## Technologies Used

- Apache PySpark
- Python
- Machine Learning
- Linear Regression
- Microsoft Power BI
- Data Cleaning and Feature Engineering
- Data Visualization

## Project Files

The repository contains the following project deliverables:

- Power BI Dashboard (`.pbix`)
- Power BI Dashboard Screenshots (all three pages)
- PySpark Execution Screenshots (data processing, model training, predictions, and evaluation)

## Key Highlights

- Applied distributed data processing concepts using PySpark.
- Developed a regression-based AC power prediction model.
- Evaluated model performance using R², RMSE, and MAE.
- Designed an interactive three-page Power BI dashboard.
- Analyzed the relationship between environmental conditions and renewable energy output.

## Conclusion

The project demonstrates how big data processing and machine learning can be applied to renewable energy output prediction. The Power BI dashboard provides an interactive way to explore energy generation patterns, weather conditions, and prediction performance.
