# Sales Forecasting with Prophet
This project aims to forecast sales data using Facebook's Prophet library. It provides an accurate and intuitive way to create time series forecasts, making it suitable for various business forecasting tasks.

keywords: Machine Learning, Python, Pandas, Numpy, Exploratory Analysis, Statistics, Boxplot

## Overview
The Sales Forecasting with Prophet project leverages Facebook's Prophet library to predict future sales based on historical data. By utilizing Prophet's powerful forecasting capabilities, this project helps businesses optimize inventory management, plan marketing campaigns, and make data-driven decisions.

## Installation
To install the required dependencies, run the following command:

`!pip install prophet`

Ensure that you have Python 3.6 or higher installed.

## Usage
To use this project, follow these steps:

Prepare your sales data in CSV format. The CSV file should include a date column and a sales column.

## Data
The sales data used for this project should be provided in a CSV file. The CSV file should have the following format:

![image](https://github.com/leonardohss0/sales-machine-learning-prophet/assets/62545078/648df446-701d-4cf8-926e-d167e7696765)

## Model Training
The Prophet model is trained using the historical sales data provided. During the training process, Prophet automatically detects and incorporates seasonality patterns, holidays, and other factors that can influence sales. The model is trained using the following steps:

1. Load the sales data from the input file.
2. Preprocess the data if necessary (e.g., handling missing values, smoothing).
3. Initialize and fit the Prophet model using the prepared data.
Refer to the sales_machine_learning_prophet.py script for more details.

## Evaluation and Testing
To evaluate the performance of the Prophet model, we use metrics such as mean absolute error (MAE) and root mean squared error (RMSE). These metrics help us assess the accuracy of the forecasts generated. Additionally, visual inspection of the predicted sales compared to the actual sales provides insights into the model's performance.

## Results
The forecasting results are saved in the specified output file (predictions.csv). These predictions provide insights into the expected sales for future time periods based on the historical data and the trained Prophet model. Visualizations and graphs can be generated to visualize the predicted sales alongside the actual sales data.

## Documentation
https://research.facebook.com/blog/2017/2/prophet-forecasting-at-scale/
https://docs.aws.amazon.com/pt_br/forecast/latest/dg/aws-forecast-recipe-prophet.html
