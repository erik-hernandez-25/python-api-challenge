This project contains two Jupyter Notebooks.

The one called "WeatherPy" is intended to randomly look for over 500 cities all over the world using cities python library and getting different weather variables such as: Temperature, Max Temperature, Humidity, Cloudiness and Wind Speed.
Then this variables are plotted into a scatter plot against latitude to show the behavior around the globe.

At the end, it also shows a linear regression model for each variable but making a distinction between southern and northern emisphere.

-------------------------------------

The second notebook called "VacationPy", uses the city list from above as input.
This program is intended to map Humidity levels using heatmaps layer from gmap python library. 
And then to shor the list according to a set of criteria that will define the ideal weather for vacations.

With the shorted list, using Google Places API we looked for lodging within 5000m and add those places to the heatmap figure.

-------------------------------------


Don't forget to include your API KEYs for openweather API and Google Places API in a separate file.



