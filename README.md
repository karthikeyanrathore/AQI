# Effect of COVID-19 on Air Quality Index

## Introduction
AQI(air quality index) is a metric to measure or compute how polluted the air is around the area. Air quality index is categorised into 6 groups, above 300 aqi indicates very poor air around the area,  which alerts the risk of public health and may affect people with lung or heart diseases. In this project, we will be analysing the impact of covid-19 on air quality index and predict air quality using various machine learning models, time series forecasting  models and deep learning models. We will be collecting our data from the Central Pollution Control Board which includes air quality index  from various cities in India from 2015-2020. We are planning to do research and analysis on how much covid-19 will impact the air quality in India in future. We will examine the influence before and after covid-19 in air quality in India. We will investigate/compare all the models using various evaluation metrics and try to improve the performance of models.  Also we are planning to build a website, the website will forecast the air quality index in Delhi only. In the future, we will expand to various other cities in India. We will be hosting our website on AWS cloud. To summarise we have two datasets, first dataset includes all the cities in India, second dataset contains various locations in delhi and we will do research and analysis on both these dataset separately.


## Research
Effect of COVID-19 on Air Quality Index.

* Model
    * inpur feature: ..
    * output feature: PM2.5

* Data
    * India - kaggle (https://www.kaggle.com/rohanrao/air-quality-data-in-india?select=city_day.csv)
    * delhi - https://aqicn.org/data-platform/register/
    * source: Delhi Pollution Control Commitee (Government of NCT of Delhi) https://cpcb.nic.in/ 

* NAQI (National AQI) / how india calculates AQI?
    * https://pib.gov.in/newsite/PrintRelease.aspx?relid=110654

## Architecture
1. getting data
2. pre-processing
3. visualize
4. models train & fit
5. evaluation metrics
6. model selection

## Miscellaneous
* provide API for AQI
* competition: https://analyticsindiamag.com/how-this-ai-startup-is-providing-real-time-air-quality-data-to-combat-pollution/
 * what factors/pollutants were responsible in air for COVID19 morality rate? are they inter-connected .there must be some correlation between them?..
   * READ THIS - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7711355/

## Links
- https://www.kaggle.com/sanchitkarakoti/air-quality-index-by-states (EDA)
- https://smartairfilters.com/en/blog/difference-pm2-5-aqi-measurements/ (PM2.5 vs aqi)
- https://github.com/caciitg/Air-Quality-Index-Prediction
- https://aqicn.org/data-platform/covid19/verify/9fbd8433-2ab9-403d-9392-43851e866615 (data set)
- https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7525347/#s0010
- https://www.kaggle.com/rohanrao/air-quality-data-in-india?select=city_hour.csv (data set)
- https://aqicn.org/data-platform/covid19/
- https://data.gov.in/resources/location-wise-daily-ambient-air-quality-delhi-year-2011
- https://github.com/SN786/India-Air-Quality-Data-Analysis
- https://github.com/mimansha98/AQI-Prediction-before-and-after-Lockdown-of-COVID-19-in-India (SARIMA and LSTM model)
- https://github.com/hellomasaya/air-pollution-in-delhi (SARIMAX model)
- https://github.com/hellomasaya/AQI-and-effect-of-lockdown
- https://en.tutiempo.net/climate/ws-427310.html (dataset scrape)
- https://aqicn.org/data-platform/register/ (dataset)
