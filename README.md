# LinearRegression
## Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short-term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain itself in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
The purpose is to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

 - Which variables are significant in predicting the demand for shared bikes?
How well do those variables describe the bike demands
 - Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


Business Goal:
To model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Conclusions
- From the final model, it is found that the top 3 features that contribute significantly towards
explaining the demand for shared bikes are the ‘year 2019’, ‘temperature’, and ‘spring’.
- Other variables that have a significant impact on the predictor variable on the dependent variables are: 
    - workingday: If it is a working day then more bikes are rented
    - temperature: outside temperature impacts significantly the number of bikes rented
    - humidity has a negative correlation with the number of bikes rented.
    - windspeed has a negative correlation with the number of bikes rented.
    - seasons(spring and winter) Here spring has a negative correlation with the number of bikes rented having a value (-0.63) and winter has a correlation of value (0.082).
    - weather situation (light rain/snow and misty-cloudy) has a negative correlation with the number of bikes rented.
    - months (November, December, and January) have a negative correlation with the number of bikes rented, but July has a positive correlation with the rented bikes
    - weekday(Monday) shows a negative correlation with the number of bikes rented.
    - year (2019) has a very strong positive correlation with the number of bikes rented

  
## Technologies Used
- matplotlib - version 3.3.4
- numpy - version 1.20.1
- pandas - version  1.2.4
- seaborn - version 0.11.1
- statsmodels - version 0.12.2
- scikit-learn - version 0.24.1

## Contact
Created by [@RezonChakraborty] - feel free to contact me!
