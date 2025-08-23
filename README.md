Obesity Rate Prediction Using Linear Regression on CDC Dataset
About the Project
This project uses linear regression to predict population-level obesity rates (% of adults with BMI ≥30) based on behavioral proxies from the CDC's Nutrition, Physical Activity, and Obesity dataset (from the Behavioral Risk Factor Surveillance System, BRFSS). It analyzes trends in factors like food intake (low fruit/vegetable consumption) and exercise (no leisure-time activity) to estimate obesity rates across groups (e.g., by state, year, demographics).

The goal is to provide insights into how lifestyle factors correlate with obesity, using publicly available data. This is a population-level model, not for individual predictions. Built with Python, scikit-learn, and pandas.

Key Features
Data preprocessing: Filtering, pivoting, and imputation for aggregated survey data.

Model: Simple linear regression.

Evaluation: R² and RMSE metrics.

Visualization: Scatter plot of actual vs. predicted values.

Getting Started
Dependencies
Python 3.8+

Libraries: pandas, scikit-learn, numpy, matplotlib

Dataset: CDC Nutrition, Physical Activity, and Obesity (download from Kaggle: https://www.kaggle.com/datasets/spittman1248/cdc-data-nutrition-physical-activity-obesity)

Model Details
Algorithm: Linear Regression (scikit-learn).

Evaluation Metrics:

R²: Proportion of variance explained (aim for 0.4–0.6).

RMSE: Average prediction error (e.g., 5–10%).
