
# Vehicle MPG Prediction 🚗📈

# Project Overview

This project is all about predicting the miles per gallon (MPG) that a vehicle can achieve based on various attributes. We've used machine learning to build a predictive model for this purpose.
# Introduction 🚀

The project aims to predict MPG, an important metric for assessing a vehicle's fuel efficiency. Predicting MPG can provide insights into the factors affecting fuel consumption in vehicles.

# Data 📊

The dataset contains information about various vehicles and includes the following attributes:

* Cylinders: Number of cylinders in the engine.

* Displacement: Engine displacement (in cubic inches).

* Horsepower: Vehicle's horsepower.

* Weight: Vehicle weight (in pounds).

* Acceleration: Vehicle acceleration (0-60 mph time in seconds).

* Model Year: Year of vehicle manufacture.

* Origin: Car's origin (1 for American, 2 for European, 3 for Japanese).

# Data Preprocessing 🛠️

The dataset was loaded and inspected to check for missing values and data types. Missing values in the "Horsepower" column were replaced with the median value. The "Horsepower" column was converted to the integer data type.

The "Origin" column was encoded into three binary columns (Origin_America, Origin_Europe, Origin_Japan) to make it suitable for machine learning.

# Exploratory Data Analysis 📈

Exploratory data analysis was conducted to understand the relationships between different attributes and the target variable (MPG). Visualizations, including scatter plots, were created to visualize these relationships.

# Machine Learning Model 🤖

A Linear Regression model was employed to predict MPG. This model learns the relationships between the attributes and the target variable from the training data.

# Model Evaluation 🧐

The model's performance was evaluated using Mean Squared Error (MSE) and Root Mean Squared Error (RMSE) metrics. The RMSE value of approximately 3.03 indicates the model's prediction error.

The model's predictions were visualized against the actual MPG values for a subset of attributes.

# Conclusion 🎉

This project demonstrates how machine learning can predict vehicle MPG based on various attributes. The model achieved an accuracy of approximately 84.33% on the test data, indicating its ability to make reasonably accurate predictions. Understanding the factors influencing MPG can be valuable for consumers and manufacturers in improving fuel efficiency. 🚗💨
## 🔗 Links
[![portfolio](https://img.shields.io/badge/view_my_notebook-000?style=for-the-badge&logo=github&logoColor=white)](https://nbviewer.org/github/Harinivas44/Vehicle_MPG_Prediction/blob/main/Linear_Regression.ipynb)
