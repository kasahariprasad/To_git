# Bike Sharing Case study
> This is a brief case study done on data of bike sharing company. Based on the analysis there are some insights drawn from the data which will help to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information

Essentially, the company wants —

- To understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.

- To understand the factors on which the demand for these shared bikes depends.

- To understand the factors affecting the demand for these shared bikes in the American market.

- The company wants to know:
        * Which variables are significant in predicting the demand for shared bikes.
        * How well those variables describe the bike demands
        
- The dataset being analysed for this case study is "day.csv" file


## Conclusions
- Linear relation between variables 'temp','atemp' and 'cnt' 
- As per analysis influencers are temperature,weather situation(weathersit_3),year
- cnt =  0.1014 + (**yr** × 0.230846) + (**workingday** × 0.0470) + (**temp** × 0.4978) - (**windspeed** × 0.1519) + (**season2** × 0.0825) + (**season4** ×0.1551) + (**mnth9** × 0.094743) + (**weekday6** ×0.1130) - (**weathersit2** × 0.0855) - (**weathersit3** × 0.2907)
- cnt is total number of bike shared or given free and the total numbers of bikes are as per above formulae
- As per analysis major influencers are temperature,weather situation(weathersit_3),year
       where weathersit_3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds


## Technologies Used
- Python Libraries - pandas, numpy, seaborn, matplotlib,MinMaxScaler,variance_inflation_factor,train_test_split,RFE,LinearRegression
- Exploratory Data Analysis - Univariate analysis, univariate segmented analysis, bivariate analysis
- Machine learning - ML models,sklearn.model_selection


## Acknowledgements
Give credit here.
- This project was done as a case study for UPGRAD masters course on AI ML.


## Contact
Created by [@kasaprasad] - feel free to contact me!

