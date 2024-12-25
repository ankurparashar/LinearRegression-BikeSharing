# LinearRegression-BikeSharing
This repository contains the BikeSharing bookings prediction solution using Machine Learning technique as linear regression.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#contact)

## General Information
#### Problem Statement: 
Consider a organization which runs a bikesharing company and willing to utilize the machine learning technique to understand the factors which are affecting the demand of bikesharing. Our objective is to find the following.
- Find the variables those are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

#### Business Goal
Model the demand for shared bikes with the available independent variables. It will be used to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way to understand the demand dynamics of a new market. 
  
#### Data
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

## Conclusions
Features which are affecting the demand are:
- Temprature
- Season: Spring
- Season: winter
- Humidity
- Weather: mist
- Weather: light-snow, light-rain
- Month: Janurary
- Month: July
- Month: September
- Windspeed
- WeekDay: Sunday
-	year
###### Equation of Best Fitted line can be determined as
cnt = 0.2317year + 0.4614temp - 0.1446humidity - 0.1771windspeed - 0.1006spring + 0.0510winter - 0.0408jan -0.0733jul + 0.0566sep - 0.2483light_snowrain -0.0569mist - 0.0417sun

## Technologies Used
- numpy 
- pandas
- matplotlib
- seaborn
- statsmodels
- sklearn
- scipy

## Contact
Created by [[@ankurparashar](https://github.com/ankurparashar)] - feel free to contact me!
