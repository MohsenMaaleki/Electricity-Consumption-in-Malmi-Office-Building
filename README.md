# Electricity Consumption Prediction for Malmi Office Building

## Overview

This project involved analyzing electricity and heating consumption data from the Malmi office building to predict energy usage patterns based on weather and environmental factors. Multiple machine learning regression models were developed and evaluated, with the Random Forest Regressor demonstrating the strongest performance.

The goal was to gain insight into the drivers of energy consumption in order to guide sustainability efforts and optimize resource usage within the building.

## Data

The dataset contains the following variables collected on an hourly basis from the Malmi office building:

- Electricity consumption
- Heating consumption 
- Outdoor air temperature
- Outdoor relative humidity
- Wind speed
- Wind direction

The raw data was preprocessed to handle missing values and convert quantities to consistent units.

## Methodology

The project methodology consisted of:

1. Exploratory data analysis
   - Data visualization
   - Statistical analysis
   - Correlation analysis
2. Feature engineering
   - Scaling
   - Normalization 
3. Model development
   - Linear regression
   - Decision tree regression
   - Random forest regression 
   - Gradient boosting regression
4. Model evaluation
   - Mean squared error
   - Mean absolute error
   - R-squared score

## Usage

The Jupyter notebook containing the data analysis and modeling code can be found here:

[Machine_Learning.ipynb](https://github.com/MohsenMaaleki/Electricity-Consumption-in-Malmi-Office-Building/blob/main/Machine_Learning.ipynb)

The notebook provides detailed documentation and discussion of the process and outcomes.

To replicate the analysis, clone the repository and run the notebook with the required Python packages installed, including `pandas`, `numpy`, `scikit-learn`, and `plotly`.

## Key Findings

- The Random Forest Regressor achieved the lowest MSE and MAE, and the highest R-squared score, indicating it was the top performing model.
- Air temperature and humidity demonstrated the strongest correlation with electricity consumption.
- Additional feature engineering and hyperparameter tuning could further enhance model accuracy.

## Future Work 

Potential areas for future investigation include:

- Incorporating additional data like occupancy, equipment usage, or metadata
- Testing long short-term memory (LSTM) networks for time series forecasting
- Deploying the models to create a predictive system integrated with building management infrastructure

Overall this project demonstrated the viability of using machine learning for energy analytics and identified specific models worthy of further optimization. The insights gained can support improved decision making around sustainability initiatives.
