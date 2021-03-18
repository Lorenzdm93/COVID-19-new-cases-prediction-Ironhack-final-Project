# COVID-19-new-cases-prediction---Ironhack-final-Project

<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Title of My Project
*Prediction of COVID-19 new cases worldwide - An early-stage vaccination evaluation*

*Data Analytics Full-Time 2021, Ironhack GmbH*

## Content
- [Dataset](#dataset)
- [Cleaning](#cleaning)
- [Analysis](#analysis)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
I want to use machine learning to predict future number of covid cases using features such as weather data, vaccinations, google mobility data and demographics.
I will use one of the model from the SARIMAX family in order to predict a time series. I will automate and run my function on a dataframe containing all the countries in the world. (#project-description)

## Hypotheses / Questions
It is possible to use ML to predict future covid cases? how relevant is the vaccination in its early stages in predicting this?(#hypotheses-questions)

## Dataset
-'Our World in data' for multiple .csv files directly downloaded from the website
-Weather dataset from Kaggle

## Cleaning
I did not have NaNs because the dataset is curated and updated daily but I had to deal with high stack on 0 which is my case where to be left there as indicate progression of certain features over time

## Analysis
data cleaning,
EDA,
feature engineering,
scaling and transforming,
building the model,
validation,
automation

## Model Training and Evaluation
ARIMAX model has been trained for each country and it prints out a summary in which you can evaluate the performance of your model. I have additionally shown the distribution of my rmse. Having some bad prediction and therefore some high rmse drives my average rmse up but plotting a distribution or all the rmse shows that most of them are stacked near the 0. Alternative validation procedure would be the K-walk for time series.

## Conclusion
It is indeed possible to get good prediction with ML on this topic and vaccination is usually the best predictor even in its early stages. This is good news because it implies that spread of virus is indeed directly dependant on the level of vaccination of the population hence manageble through it.

## Future Work
-Optimized out-of-sample predictions already. I had to infer future measures of my Xs so I only performed that on one country I was confident predicting rate of vaccination and measures adopted (Italy).
-Automatically updating the dataset in line with the github repo and get daily prediction, also backtesting previous predictions over time.
-Integrate seasonal component If 2 years of data will be available.

## Workflow
Data collection and cleaning, EDA, feature engineering, ML building and evaluation.

## Organization


## Links



[Repository](https://github.com/)  
[Slides](https://slides.com/)  
[Trello](https://trello.com/en)  
