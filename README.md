# python-api-challenge
Part I - WeatherPy:
The aim is to create a representative model of weather across world (500+) cities.The Python script utilizes python library, citypy, makes API calls to OpenWeatherMap to retrieve weather data. The first objective is to build a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude
The next objective is to run linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).

Part II - VacationPy:
This part deals with working with weather data to plan future vacations. Jupyter gmaps and the Google Places API have been used for this part of the assignment.A heat map is generated displaying the humidity for every city from part I.This is further narrowed down to find ideal weather condition.Using Google Places API is used to find the first hotel for each city located within 5000 meters of selected coordinates.Finally, the hotels are plotted on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
