# weather_api_project

This project analyzes the the certain weather patterns for a random list of cities on the planet. The goal of the project is to establish with data that the weather patterns for cities at the equator differs from those that are further away from the equator.

This project utilizes Citipy and the OpenWeatherMapy API to generate a random set of coordinates, find the nearest city, and then read json files to find the temperature, humidity, cloudiness, and windspeed for the city. A minimum of 500 cities are studied and evaluated. Findings are as follows:

1. Windspeed appears to decrease as you get closer to the equator. An interesting observation of this dataset is that windspeed appears to decrease the closer to the equator you are. Why is this? More analysis will need to be done to determine if any there is any statistically significant correlation, but this observation raises interesting questions.

2. Cloudiness and latitude is a data comparison that would benefit from a time study. While there there appear to be a large number of cities studied that had no clouds across all latitude ranges, cloudiness could be a factor subject to a far more variability from day-to-day. In order to draw a more definitive observation, a time study would be appropriate.

3. The cities closer to equator have higher humidity levels. Humidity levels are relative to temperature. While cities further from the equator could have a wide range of humidity values (from closer to 0 to closer to 100), the cities closer to the equator had a much smaller range. No cities had a humidity level close to 0, and many were bunched closer to 70-80 percent.
