# Regression-Analysis-using-R
This project aims to build a regression model to predict the counts of bikes rented per hour
### Collaborators
1. Atrayee Dutta Chowdhury
2. Purvita Mandal
3. Raka Sen
4. Raktima Dey
### Introduction
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes
### Objective
To predict the count of bikes rented per hour using a regression model
### Dataset used
The dataset contains count of public bikes rented at each hour in Seoul Bike haring System with the corresponding Weather data and Holidays information. It is available at UCI Machine Learning Repository. The link to the dataset is : databases/00560Parent DirectorySeoulBikeData.csv
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.
We wish to analyse the data and fit a proper model to the dataset 
### Description of the variables
The variables are :
Date : year-month-day
Rented Bike count - Count of bikes rented at each hour
Hour - Hour of the day
Temperature-Temperature in Celsius
Humidity -  Percentage of Humidity
Windspeed – Speed of the wind (m/s)
Visibility – Visibility (10m)
Dew point temperature -  Dew Point Temperature ( in Celsius)
Solar radiation -  Solar  Radiation in (MJ/m2)
Rainfall -Amount of rainfall (in mm)
Snowfall -Amount of snowfall (in cm)
Seasons - Winter, Spring, Summer, Autumn
Holiday - Holiday/No holiday
Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)
### Working
Fitted a Multiple Linear Regression Model on the dataset to predict the number of bikes rented per hour. On encountering violations to CLRM, provided various remedies to them. On comparing RMSE of the various regression techniques, it was observed that each of the techniques had very close RMSEs, with the reduced model having the least RMSE value of 0.0175. Hence we conclude that the reduced model is the best model among the above models for this dataset.
