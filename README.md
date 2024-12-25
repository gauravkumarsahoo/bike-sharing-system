# Bike Sharing Model
> The objective is to develop a robust linear regression model to predict the demand for shared bikes (cnt) based on the available independent variables. This model will enable the company to:

> 1. Understand how various factors, such as weather conditions, seasonal variations, etc, influence bike-sharing demand.
> 2. Leverage the model to forecast demand dynamics in new markets, helping the comapny to plan resources effectively.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information

- **Background of the Project:**  
  The growing trend of bike-sharing systems in urban environments has raised the need for efficient demand forecasting models. Accurate predictions of bike demand can help optimize the number of bikes available at different locations, improving customer satisfaction and operational efficiency.

- **Business Problem:**  
  The project aims to solve the problem of predicting bike-sharing demand in a city. The bike-sharing company needs to know how weather, season, holidays, and other factors influence the number of bikes needed. This helps the company plan for resources, manage bike availability, and optimize operations in different weather conditions and seasons.

- **Dataset:**  
  The dataset contains information about various factors like weather conditions, temperature, humidity, windspeed, season, and holidays, and their impact on bike-sharing demand (represented as "cnt"). This dataset includes both continuous variables (e.g., temperature, windspeed) and categorical variables (e.g., season, holiday).

## Conclusions
* For Training Set
  * R-squared value: 0.836
  * Adjusted R-squared value: 0.832

* For Testing Set
  * R-squared value: 0.805
  * Adjusted R-squared value: 0.795

* Best fitted line
  * _cnt = 0.1996 + (0.2335 * yr) - (0.0980 * holiday) + (0.4915 * temp) - (0.1480 * windspeed) - (0.0669 * spring) + (0.0453 * summer) + (0.0831 * winter) - (0.0524 * Jul) + (0.0767 * Sep) - (0.2852 * light_rain) - (0.0816 * mist)_

## Technologies Used
- Pandas - version 2.2.3
- Matplotlib - version 3.9.4
- Seaborn - version 0.13.2
- Sklearn - version 1.6.0
- Statsmodels - version 0.14.4

## Acknowledgements
This project was done as an assignment provided by upGrad.


## Contact
Created by [@gauravkumarsahoo] - feel free to contact me!