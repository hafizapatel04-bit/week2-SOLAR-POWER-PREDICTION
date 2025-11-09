# week2-SOLAR-POWER-PREDICTION
Solar Power Output Prediction  This project uses machine learning to predict AC/DC power output of a solar plant based on weather sensor data. 
Solar Power Output Prediction
Overview

This project predicts AC/DC power output of a solar plant using weather sensor data and machine learning. It demonstrates a complete workflow from raw data to predictions and performance evaluation.

Dataset

Weather Data: Contains ambient and module temperatures, irradiation, and timestamp.

Plant Generation Data: Contains AC/DC power, daily and total yields, and timestamp.

Features Used

Ambient Temperature

Module Temperature

Irradiation

Hour, Day, Month (extracted from timestamp)

Methodology

Data Preprocessing:

Converted DATE_TIME to datetime objects.

Merged weather and plant generation data on timestamps.

Selected numeric features for modeling.

Modeling:

Used XGBoost Regressor to predict AC/DC power output.

Split data into train and test sets (80%-20%).

Evaluation:

Calculated RMSE and R² score to measure prediction accuracy.

Optional: plotted predicted vs actual values.

Usage

Clone the repository.

Place the CSV files (Weather_Data.csv and Plant_Generation_Data.csv) in the working directory.

Run the notebook or Python script to train the model and evaluate predictions.

Results

Provides an accurate prediction of solar plant power output using machine learning.

Can be extended with additional features, lag variables, or other models.
