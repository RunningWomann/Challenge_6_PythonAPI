# Challenge_6_PythonAPI
Part I - WeatherPy
Create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, you’ll be utilizing a simple Python library, Citipy, and the OpenWeatherMap API.

1. To create a series of scatter plots to showcase the relationships between location and temperature, humidity, wind speed, and cloudiness.

2. To run linear regression on each relationship for the northern and southern hemispheres.

Requirement:
Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude.
Perform a weather check on each of the cities using a series of successive API calls.
Include a print log of each city as it’s being processed with the city number and city name.
Save a CSV of all retrieved data and a PNG image for each scatter plot.

Part II - VacationPy
Work with weather data created in Part I to plan future vacations. Use jupyter-gmaps and the Google Places API for this part of the assignment. Create a heat map that displays the humidity for every city from Part I.
