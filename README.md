# Bike Sharing Assignment
> Project by Géraldine Bengsch (First Upgrad case study) <br>
>
> This project uses Regression Analysis to build a multiple linear regression model for the prediction of demand for shared bikes:
> - Which variables are significant in predicting the demand for shared bikes
> - How well the variables describe the bike demands
>
> The project contains:
> - Data Analysis notebook
> - A folder containing images used (Visualisations are our own, picture is from Unsplash)
> - The data set `day.csv`
> - The data dictionary `Readme.txt`


## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#contact)


  
## General Information
![Photo by <a href="https://unsplash.com/@f_meloni?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Fernando Meloni</a> on <a href="https://unsplash.com/s/photos/bike-lending?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
](img/fernando-meloni-va6b5ag3Jvo-unsplash.jpg)
  

- **General information:** 
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario

- **Background:** 
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

- **Business problem:**
Aim is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations.

## Assignment Steps performed in the notebook

## Data visualisations
- perform EDA to understand various variables
- check correlation between the variables and

## Data preparation
- create dummy variables for all categorical features
- divide the data to train and test
- perform scaling
- divide data into dependent and independent variables

## Data modelling and evaluation
- create linear regression model using mixed approach (RFE & VIF/p-Value)
- check the various assumptions
- check the adjusted r-square for both train and test data
- report the final model



## Conclusions
Please see the notebook for more detailed insights.
1. `temp` has the highest coefficient, with 0.50. This means, that when the temperature increases by one unit, the count of bike rentals also increases by 0.50. 
2. next highest coefficient is `yr` with 0.23. There are also negative coefficients which show a relation in the opposite direction. 
3. The largest negative coefficient is `cloudy` with -0.30.

Temperature and weather are important factors the company should consider when making business decisions. It would also seem that the demand for bikes is growing by passing years. The pandemic is hopefully not going to diminish this demand, so that the company can recover.



## Technologies Used

![Python](https://img.shields.io/badge/Python-3.10-informational?style=flat&logoColor=white&color=2bbc8a)
![NumPy](https://img.shields.io/badge/NumPy-1.21.5-informational?style=flat&logoColor=white&color=2bbc8a)
![Pandas](https://img.shields.io/badge/Pandas-1.3.5-informational?style=flat&logoColor=white&color=2bbc8a)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5.1-informational?style=flat&logoColor=white&color=2bbc8a)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11.2-informational?style=flat&logoColor=white&color=2bbc8a)
![sklearn](https://img.shields.io/badge/Sklearn-1.0.2-informational?style=flat&logoColor=white&color=2bbc8a)
![statsmodels](https://img.shields.io/badge/statsmodels-0.13.1-post1-informational?style=flat&logoColor=white&color=2bbc8a)
![scipy](https://img.shields.io/badge/scipy-1.8.0-post1-informational?style=flat&logoColor=white&color=2bbc8a)



## Contact
Created by [@GeriNZ](https://github.com/GeriNZ) - feel free to contact me! <br>
Student at UpGrad: *Master of Science in ML and AI* <br>
© 2022


