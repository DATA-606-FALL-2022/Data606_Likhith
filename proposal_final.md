 # Predicting Rain in Australia
 
 ## Introduction

The Australian Commonwealth Bureau of Meteorology provided a year's worth of daily weather observations gathered from the Canberra airport in Australia, which were then processed to produce this sample dataset for demonstrating data mining using Python.

Next data processing, the goal variable RainTomorrow (which indicates whether rain will fall the following day—No/Yes) and the risk variable RISK MM were created (how much rain recorded in millimetres). On the raw data, various transformations were carried out. The dataset is fairly little and only helpful for demonstrating different data science procedures in a reproducible manner.
RainTomorrow is the target variable to predict. It means -- did it rain the next day, Yes or No? This column is Yes if the rain for that day was 1mm or more.
        
The Australian Commonwealth Bureau of Meteorology owns the uderlying dataset, which is distributed as part of the rattling package with permission.

## Goal of the Project 

Rain has a significant impact on a variety of plans, including crop growth for farmers, weekend getaways for families, and airline logistics. For the benefit of many stakeholders, a weather app can employ an accurate prediction model to determine if it will rain.
        
## Importance of current study:

Develop a predictive classifier to predict the next-day rain on the target variable Rain Tomorrow.
This dataset contains about 10 years of daily weather observations from many locations across Australia.

The goal variable to be predicted is RainTomorrow. Does it indicate that it rained the following day, Yes or No? If the amount of rain that day was 1 mm or greater, the column is set to Yes.

## Problem Type

Classfication Problem Using Machine Learning(Predict next-day rain by training classification models on the target variable RainTomorrow)

## Dataset Source & Acknowledgements 

* Observations were drawn from numerous weather stations. The daily observations are available from http://www.bom.gov.au/climate/data.
* An example of latest weather observations in Canberra: http://www.bom.gov.au/climate/dwo/IDCJDW2801.latest.shtml

* Definitions adapted from http://www.bom.gov.au/climate/dwo/IDCJDW0000.shtml
* Data source: http://www.bom.gov.au/climate/dwo/ and http://www.bom.gov.au/climate/data.

* Copyright Commonwealth of Australia 2010, Bureau of Meteorology.


* This dataset contains about 10 years of daily weather observations from many locations across Australia.

### Categorical Features
<ol type="1">
<li>Date: The date of observation</li>
<li>Location: The common name of the location of the weather station</li>
<li>RainToday: Boolean: 1 if precipitation (mm) in the 24 hours to 9am </li>exceeds 1mm, otherwise 0</li>
<li>WindDir3pm: Direction of the wind at 3pm</li>
<li>WindDir9am: Direction of the wind at 9am</li>
<li>WindGustDir: The direction of the strongest wind gust in the 24 hours to midnight</li>

### Numerical Features
<li>MinTemp: The minimum temperature in degrees celsius</li>
<li>MaxTemp: The maximum temperature in degrees celsius</li>
<li>Rainfall: The amount of rainfall recorded for the day in mm</li>
<li>Evaporation: The so-called Class A pan evaporation (mm) in the 24 hours to 9am</li>
<li>Sunshine: The number of hours of bright sunshine in the day.</li>
<li>WindGustSpeed: The speed (km/h) of the strongest wind gust in the 24 hours to midnight</li>
<li>WindSpeed9am: Wind speed (km/hr) averaged over 10 minutes prior to 9am
<li>WindSpeed3pm: Wind speed (km/hr) averaged over 10 minutes prior to 3am
<li>Humidity9am: Humidity (percent) at 9am
<li>Humidity3pm: Humidity (percent) at 3pm
<li>Pressure9am: Atmospheric pressure (hpa) reduced to mean sea level at 9am</li>
<li>Pressure3pm: Atmospheric pressure (hpa) reduced to mean sea level at 3pm</li>
<li>Cloud9am: Fraction of sky obscured by cloud at 9am. This is measured in "oktas", which are a unit of eigths. It records how many eigths of the sky are obscured by cloud. A 0 measure indicates completely clear sky whilst an 8 indicates that it is completely overcast</li>
<li>Cloud3pm: Fraction of sky obscured by cloud (in "oktas": eighths) at 3pm. See Cload9am for a description of the values</li>
<li>Temp9am: Temperature (degrees C) at 9am</li>
<li>Temp3pm: Temperature (degrees C) at 3pm</li>

## Target Variable
Chance of Rainfall Tomorrow is my target variable.
The question I would like to answer is "Did it rain tomorrow?" (1 = yes, 0 = no )


## Analysis:
<ol type="1">
  <li>Extraction data from dataset and converting into pandas dataframe.</li>
  <li>Print the shape and size of the converted dataframe.</li>
  <li>Describe various features of dataset using describe function.</li>
  <li>Clean and tranform the dataframe uing various machine learning library like sklearn,numpy,pandas.</li>
  <li>Plot various plots to understand relationship between various features of dataset.</li>
  <li>After applying all the pre-processing steps in our dataset we have to create our machine learning column.</li>
  <li>Split data into training and testing data.</li>
  <li>Choose an approprite machine learning model using K-fold cross validation Algorithm (k-fold cross validation is a procedure used to estimate the skill of the model on new data).</li>
  <li>Apply hyperparameter tunning in all those model who last preformed best in K-fold cross validation algorithm.</li>
  <li>Identify the potential features in our dataset.</li>
  <li>The model that perform best in hyperparameter tunning will be chosen as our machine learning model.</li>
</ol>

## Outcome:
 
 In this research, it was examined whether machine learning techniques could be used to solve the issue of rainfall forecasting in the particular situation of Australia.This kind of technique has been used in earlier research [28–34] with various kinds of monthly, annual, and other time period datasets in locations other than Australia. The regions of Victoria and Sydney were the study venues.The potential benefits of using machine learning techniques as tools to replace traditional rain forecasting techniques (they also have some advantages over classical forecasting methods, such as the possibility of estimating the reliability of the results using the Indicators, Performance Key, or the possibility of adjusting the performance of the algorithms by manipulating their input parameters, which allows them to be adapted to particular cases).



## References: 
<ol type="1">
<li>https://rdrr.io/cran/rattle.data/man/weather.html</li>
<li>https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package</li>



</ol>













 
