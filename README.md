# Weather-Data-Analysis
New Delhi Weather Data Analysis

## BACKGROUND
Over the past few decades climatologists have put a great deal of effort into understanding and predicting the climate data. They continuously analyze the data and suggest trends and patterns in climate and weather conditions of a region. These insights can be very beneficial in finding seasonal patterns and climate changes over time. The objective of this project is to analyze the weather of New Delhi, India over the past few years using time series analysis techniques. Delhi is a region of particular interest because of the rapid urbanization and development in the city. 

The analysis aims to find weather patterns, temperature changes and other significant weather conditions in the city. Temperature changes directly relate to and indicate global warming, and hence the goal of this research is also to find out if the city has contributed or experienced global warming over the past few years. 

Increasing urbanization, population, and economies have been witnessed to cause a huge impact on the environment, making it essential for data collection and timely analysis to make appropriate decisions for the future. Humans have had a considerable impact on the climate since industrialization resulting in increased warming on the planet. Finding Conveying these messages with accurate statistics puts more meaning to the grave situation we are in now, highlighting the alarming rate of climate change. The COP26 put forward the urgency to reach net zero emissions by mid-century by keeping 1.5 degrees within reach.

There are a few researches that have been done in the past for different time intervals regarding the meteorological data analysis for Delhi, and one study shows the increasing average maximum temperature and decreasing minimum temperature over 1961-1990. 
While another research by Surendra et. al. concluded that there is an increase in both the minimum and maximum temperatures over the 44 years’ time period that they analysed. 

My analysis will find weather patterns, seasonality, and autocorrelation from the data, using statistical tests and visualization techniques to represent the findings using bar plots and time series plots. The temperature analysis in my study will observe minimum and maximum temperature shifts if there are any, and if they relate to any of other studies that have been published before.


## DATASET DESCRIPTION

The data used for the analysis is weather data for New Delhi, India. It is the capital of India and lies in the northern region of the country, with its neighboring states being Haryana and Uttar Pradesh. 

The data is collected from Kaggle, but it is sourced from Wunderground website which allows us to easily download the historical weather data using their easy to use api. It is a website by a commercial company called “Weather Underground” with its base in San Francisco, U.S. The Weather Underground is a subsidiary of the multinational technology company IBM. They collect and report real-time weather data for major cities, with their data being sourced from National Weather Service (NWS) and over 250,000 personal weather stations. 
The dataset has 20 columns and 100990 rows, and holds hourly summaries of weather from 1996 to 2017 in a csv format. The date range of the data is from 11/01/1996 to 04/24/2017. The datatypes in the dataset are datetime, character, integer and double. 
The data contains features like datetime, weather condition, temperature, precipitation, humidity, pressure, fog, dew, hail, snow, thunder, tornado, wind, etc. 

Important attributes which will be used majorly in the study will be datetime, weather condition, temperature and precipitation. The datetime holds data in YYYYMMDD-HH:MM format which will need to be converted into POSIXct format in order to be read properly in R, and the temperature is in degrees Celsius stored in numeric format. Weather conditions holds the data in character format with its categories being fog, smoke, thunderstorm, haze, clouds, mist, etc. 
