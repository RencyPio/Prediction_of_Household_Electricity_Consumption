# Prediction_of_Household_Electricity_Consumption
# Introduction
Household electricity usage generates massive streams of data through smart meters. Analyzing this data is important for understanding consumption patterns and predicting future demand.
This project uses Big Data Analytics and Machine Learning to process large-scale electricity data and provide accurate consumption predictions.

# Problem Statement
Traditional systems struggle to efficiently analyze large volumes of electricity data and predict future usage.

This project aims to:
* Analyze household electricity consumption patterns
* Identify trends and usage behavior
* Predict future electricity consumption using Machine Learning models

# Dataset Description
The dataset contains household electricity usage data collected at minute-level intervals.
Total Records: 2,075,259

# Features:
* Date
* Time
* Global_active_power
* Global_reactive_power
* Voltage
* Global_intensity
* Sub_metering_1
* Sub_metering_2
* Sub_metering_3

# Data Preprocessing
* The following preprocessing steps were performed:
  * Handling missing values
  * Converting Date & Time into timestamp
  * Removing invalid records
  * Feature engineering (hour, day, month, weekend)
  * Type casting to numerical format
  * Feature Engineering
* New features were created to capture consumption patterns:
  * Hour of the day
  * Day of the week
  * Month
  * Weekend indicator
These features help in identifying daily and seasonal trends.

# Machine Learning Models Used
* Linear Regression
* Random Forest Regressor

# Best Model Selection
Random Forest was selected as the best model based on:
* Lower RMSE
* Better generalization
* Ability to capture non-linear patterns


# Project Files (Google Drive)
Due to GitHub file size limitations, the complete project (including dataset and trained model) is available in Google Drive:
👉 Full Project Link:
https://drive.google.com/drive/folders/1OKV70UlJ_hIOciIkVE9cN5ORYr5wMQrd?usp=sharing

# Conclusion
This project demonstrates how Big Data tools like PySpark can process large-scale electricity data and generate meaningful insights.
Machine Learning models help in predicting consumption, enabling better energy management and planning.

This project demonstrates how Big Data tools like PySpark can process large-scale electricity data and generate meaningful insights.
Machine Learning models help in predicting consumption, enabling better energy management and planning.
