##  OpenWeatherMap Python API

This scripts connects to the OpenWeatherMap API to display weather data to visualize the weather of 500+ cities across the world of varying distance from the equator. 

## Description

The script will randomly select 500 unique (non-repeat) cities based on latitude and longitude. Next, it will display a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

### Dependencies

- random
- json
- requests
- numpy 
- pandas
- matplotlib.pyplot
- seaborn 
- citipy 

### Credentials

First, obtain an API key from https://openweathermap.org/api

### Executing program

Run the python code in Jupyter Notebook. 
