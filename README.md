# python-api-challenge
## WeatherPy Folder
The WeatherPy Folder contains the WeatherPy script, which generates a list of coordinates and uses the OpenWeatherMap API to get the city name and information of each set of coordinates. With cities and the information for each city, a csv file called cities.csv is generated and is stored in the From there, four scatterplots are generated, and eight linear regression plots are generated and are outputed to the Images folder within the WeatherPy folder.

The scatterplots generated are
- Latitude vs Cloudiness
- Latitude vs Humidity
- Latitude vs Temperature
- Latitude vs Windspeed

The linear regression plots are divided between the Northern and Southern Hemisphere, with each Hemisphere having the following linear regression plots:
- Latitude vs Cloudiness
- Latitude vs Humidity
- Latitude vs Temperature
- Latitude vs Windspeed

## Data_output Folder
The Data_output folder contains the csv file generated by WeatherPy script.
## VacationPy Folder
The VacationPy Folder contains the VacationPy script, which analyzes the cities.csv in the Output_data folder and uses the Geoapify API to find the closest hotel to some of the cities that have ideal weather with max temperatures between 68 and 80 degrees Fahrenheit. The script generates two maps:
- a map of all of the cities, with the size of the cities' dots based on each city's humidity
- a map of cities that have the ideal weather outlined by the code, with the size of the cities' dots based on each city's humidity, as well as a hotel that is within a radius of 1000m of the city


## Citations
The script in WeatherPy.ipynb contains code from https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.figtext.html to add text to the figures.

The script in VacationPy.ipynb contains code from the following websites:
- https://holoviews.org/user_guide/Style_Mapping.html in codebox[25] to make the dots indicating the cities on the map translucent.
- https://hvplot.holoviz.org/reference/geopandas/points.html in codebox[28] to add the Hotel Name and City Name data to the info panel when you hover over the cities on the second map.
