# WeatherPy

## Background

Python script to visualize the weather of 500+ cities across the world of varying distance from the equator using CityPy, a simple Python library, and the OpenWeatherMap API.

The visualizations includce a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude Humidity (%) vs. Latitude Cloudiness (%) vs. Latitude Wind Speed (mph) vs. Latitude

The script accomplishes the following:

Randomly selects at least 500 unique (non-repeat) cities based on latitude and longitude.

Performs a weather check on each of the cities using a series of successive API calls.

Includes a print log of each city as it's being processed with the city number and city name.

Saves both a CSV of all data retrieved and png images for each scatter plot.



## Observable Trends

I.	According to the latitude vs. temperature plot, as the latitude increases at the northern hemisphere the temperature decrease plummets, when compared to the latitude increase (through negative numbers) at the southern hemisphere. This is most likely related with the percentage of lands at each hemisphere.

II.	As the two plots of “latitude vs. humidity” and “latitude vs. temperature” evaluated together, the humidity inversely correlates with higher temperature as it is evident that lower latitudes are warmer and have higher humidity.

III.	As we compare all the plots together (latitude vs. –temperature, -humidity, - cloudiness, -windspeed), we can conclude that latitude effects none of these variables but the temperature. 
