# python-api-challenge

Assignment 6 of UCI's Data Visualization Program

WeatherPy finds the weather conditions of various cities, selected with randomly generated latitude and longitude coordinates. Coordinate values are made using the Python Random module, cities are found using citipy's nearest city property, and weather data for each city is provided by OpenWeatherMap's API.

VacationPy locates the nearest hotels of the previously generated cities, sorted by ideal weather conditions for an upcoming vacation. Geolocation and heatmaps are provided by Google Places API and jupyter-gmaps.


## About
If using, download all materials provided in the repository.  

You must have API keys for OpenWeatherMap and Google Places; if these are not inputted then the scripts will not return any information.  

The OpenWeatherMap API key goes in: 'WeatherPy/api_key.py'  
The Google Places API key goes in: 'VacationPy/config.py'  

After this is done, run the provided ipynb files to generate data.  

*Note: OpenWeatherMap gives weather data for the current time and day, so running the scripts multiple times across multiple periods of time will give slightly different results.  


## Insights, Analysis

**_On average, temperatures will be higher the closer one is to the equator (0° latitude)_**

This is due to the fact that the surface of the Earth near the equator recieves the most heating from the Sun, resulting in higher temperatures of the air and water. The opposite is true for the Earth's poles.

**_Although a strong correlation isn't evident in the presented data, wind speeds will be faster away from the equator, and will reach higher speeds between 20° and 60° latitude._**

Wind speed is highly dependent on many factors, such as a city's location near the ocean or further inland, the region's topography, the region's biome, what latitude it's in, and other conditions. Therefore, the wind speeds recorded for each city are highly subject to change, and can produce mostly similar values across all latitudes.  

Based on the results created on April 28, 2022, wind speeds farther from the equator have higher speeds, with the most potential for high wind speed occuring between 20° and 60° latitude in both hemispheres.

**_There are significantly more cities to gather data from in the Northern Hemisphere than in the Southern Hemisphere._**

The Southern Hemisphere, being around 80% ocean, simply has less habitable land for large populations compared to the Northern Hemisphere. When comparing the two regions, there will always be more data points to pull from the North, which may skew the data.


## Credits

citipy
https://github.com/wingchen/citipy

OpenWeatherMap
https://openweathermap.org/

Google Maps/Places
https://developers.google.com/maps
