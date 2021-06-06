# WEATHER FORECASTING ACROSS THE WORLD
    Overview
    
Python scripts were created to visualize the weather for over 500 cities across the world at varying distances from the equator. To understand weather patterns for forecasting a series of scatter plots were created. The scatter plots depicted the relationship between Temperature versus Latitude, Humidity versus Latitude, Cloudiness versus Latitiude, and Wind Speed versus Latitude. Linear regressions for each relationship were created separating them in Northern and Southern Hemispheres. More than 500 cities were randomly selected based on there latitude and longitude to perform a weather check on each of the cities usig a series of API calls to confirm the findings of the Python scripts. The analysis used external data for comparison, that was obtained using third party APIs. Data was parsed using an OpenWeatherMap and US Census API Keys that was requested from the sources to make GET requests for JSON formatted information. Requested JSON information was converted into a PYTHON dictionary for loading into a Pandas Dataframe. A Google Maps and Places API Key was used to obtain information about geographic areas. Special attention was taken to understand rate limits and the importance of creating "test cases" prior to running large scripts. A firm understanding of 

These relationships were used to select ideal weather conditions for vacation planning. A weather check on these 500 cities using a series of successive API calls were used to retrieve and document the weather. This document could be used when considering future vacations in these cities.

To accomplish this analysis, citipy (a simple Python library), and several API 



Visual depicted the weather in these cities. 
    Results



For this analysis, an outside data source was used for my data analysis. I used GET requests, converted JSON into a Python dictionary, read and applied API documentation, signed up and used an API Key, loaded JSON from API responses into a Pandas DataFrame, successfully used Google Maps and Places API to obtain information about geographic areas, and obtained a firm understanding of how to dissect new API documentation.

