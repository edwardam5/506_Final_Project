# 506_Final_Project

## Installation

 To use this project, first clone the repo on your device using the command below: 
 
 git init
 
  git clone https://github.com/edwardam5/506_Final_Project.git
    
    
## Project Intro/Objective 
The purpose and business objective of this analysis is to aid the California government with forecasting the number of injuries for Southern Californians in order to determine the quantity and necessity of resource allocation for Southern California to reduce traffic related accidents. In order to forecast the overall trend, based on the number of injuries, the machine learning objective of this predictive time series analysis is to create and tune five time series models that can accurately predict the prospective number of injuries for Southern California. The following five time series models were employed to carry out the objective of this study: Linear Regression, Holt-Winter’s Exponential Smoothing AAA, Holt-Winter’s Exponential Smoothing ANA, ARIMA, and Neural Network. The success criteria of this analysis is to create a model with the lowest RMSE, MAE, MPE, MAPE, and MASE scores.  

## Contributors 
- Anusia Edward
- Harini Lakshmanan

## Methods Used 
- Data Mining 
- Time Series Analysis 
- Forecastive Modeling 
- Machine Learning 
- Data Visualization 

## Technologies 
- R studio  

## Project Description 
The project is a time series project in which the study aims to forecast traffic-related injuries in Southern California. 

#### Dataset Description 
The dataset “Road-Traffic-Injuries-2002-2010” was sourced as a raw csv from Healthdata.gov, which is an official website of the United States government dedicated to making health-related data more accessible. The data contains information from 2002 to 2010 about traffic-related injuries within different California based counties. The dataset contains information in regards to the annual number of fatal and severe
road traffic injuries for California. More specifically, the dataset is composed of
California’s regions, counties, county divisions, cities/towns, and census tracts. The
injury data is from the Statewide Integrated Traffic Records System (SWITRS),
California Highway Patrol (CHP), and Transportation Injury Mapping System (TIMS).
The data contains information from 2002 to 2010 along with the race/ethnicity of the
person injured in the road-traffic related injury. Additionally, the data contains the
number of injuries in the geographic area by severity (killed, sever injury) and mode of
transportation of the victim (bicyclist, bus, car/pickup, motorcycle, pedestrian, truck,
vehicles) The total population, rate of injuries over total population, and rate of injuries
over annual miles traveled.

#### Background/ Current Situation
The ability to move individuals, products, or materials from one city to another, or even one state to another, was revolutionized through the use of motorized vehicles. Essentially, travel made possible by motor vehicles supports economic and social development in many countries. Although this development allowed for a lot of growth, it is necessary to note the downside of motorized vehicles. Each year 1.35 million people are killed on roadways globally. Approximately 3,700 people are killed globally in crashes involving cars, buses, motorcycles, bicycles, trucks, or pedestrians each day, with more than half of those killed being pedestrians or motorcyclists. On a more local level, on average, there are 4,018 deaths per year in California caused by transportation accidents. Transportation related injuries, in terms of traffic collisions of motorcyclists, pedestrians, and bicyclists, are the second leading cause of death in California.
### Hypothesis 
The general hypothesis of this study is that at least one of the five time series modeling techniques utilized will result in a model that forecasts the overall trend of injuries within Southern California. More specifically, a secondary hypothesis is that the best model will be the ARIMA model with the success criteria being low scores for RMSE, MAE, MPE, MAPE, and MASE. 
### Video Presentation
Link: https://youtu.be/xzSXf6JDSyo 
