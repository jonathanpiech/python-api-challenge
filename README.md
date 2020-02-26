# weather-vs-latitude

## Summary
This repository contains two parts of a project. The first part was to use OpenWeatherMap to reverse geocode a list of about 500 cities to analyze the effects latitude had on temperature, humidity, cloudiness and wind speed. 

![alt-text](https://raw.githubusercontent.com/jonathanpiech/weather-vs-latitude/master/PyWeather/tvl.png "temperature vs. latitude")
![alt-text](https://raw.githubusercontent.com/jonathanpiech/weather-vs-latitude/master/PyWeather/hvl.png "humidity vs. latitude")
![alt-text](https://raw.githubusercontent.com/jonathanpiech/weather-vs-latitude/master/PyWeather/cvl.png "cloudiness vs. latitude")
![alt-text](https://raw.githubusercontent.com/jonathanpiech/weather-vs-latitude/master/PyWeather/wsvl.png "wind speed vs. latitude")

The second part of the project was to filter the list of cities by some weather conditions, and to create a heatmap with hotel markers using Google Maps.

![alt-text](https://raw.githubusercontent.com/jonathanpiech/weather-vs-latitude/master/PyVacation/map.png "heatmap")

## Requirements

To run `Weather.ipynb`, you need your own OpenWeatherMap API key. Create a `config.py` file in the folder with variable `api_key` to run without any changes. To run `Vacation.ipynb`, you need your own Google Maps API key. Create a `config.py` file in the folder with variable `gkey` to run without any changes.