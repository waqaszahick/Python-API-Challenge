# Python-API-Challenge
This is my first Python API challenge, and sixth over all assignment. This is a two-part challenge i.e. 'WeatherPy' and 'VacationPy'. In the first part i.e. 'WeatherPy', I performed the following tasks:
- Utilized 'Python' library and the 'OpenWeatherMap' API, in order to create a representative model of weather across world cities.
- Created a series of scatter plots to showcase the following relationships:
   * Temperature (F) vs. Latitude
   * Humidity (%) vs. Latitude
   * Cloudiness (%) vs. Latitude
   * Wind Speed (mph) vs. Latitud
- Run linear regression on the following relationships, separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and
   Southern Hemisphere (less than 0 degrees latitude):
   * Northern Hemisphere - Temperature (F) vs. Latitude
   * Southern Hemisphere - Temperature (F) vs. Latitude
   * Northern Hemisphere - Humidity (%) vs. Latitude
   * Southern Hemisphere - Humidity (%) vs. Latitude
   * Northern Hemisphere - Cloudiness (%) vs. Latitude
   * Southern Hemisphere - Cloudiness (%) vs. Latitude
   * Northern Hemisphere - Wind Speed (mph) vs. Latitude
   * Southern Hemisphere - Wind Speed (mph) vs. Latitude
- Randomly selected 500 unique (non-repeat) cities based on latitude and longitude
- Performed a weather check on each of the cities using a series of successive API calls
- Included a print log of each city as it's being processed with the city number and city name
- Saved a '.csv' file of all retrieved data and a '.png' image for each scatter plot, respectively in seperate folders

In the second part i.e. 'VacationPy', I performed the following tasks:
- Used 'jupyter-gmaps' and the 'Google Places' API for this part of the assignment
- Created a heat map that displays the humidity for every city from the Part-I (WeatherPy)
- Narrowed down the 'DataFrame' to find ideal weather condition. For example:
   * A maximum temperature lower than 80 degrees Farenheit but higher than 70 degrees Farenheit
   * Wind speed less than 10 miles per hour (mph)
   * Zero (%) cloudiness
- Used 'Google Places' API to find the first hotel for each city located within 5000 meters of my coordinates
- Plotted the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country

As final condsiderations for this assignment, I performed the following:
- Completed my analysis using a 'Jupyter' notebook
- Used the 'Matplotlib' and / or the 'Pandas' plotting libraries.
- For Part-I (WeatherPy), I included a written description of three observable trends based on the data
- For Part II (VacationPy), I included a screenshot of each heatmap I created
- Used proper labelling for my plots, including aspects like: 'Plot Titles' (with date of analysis) and 'Axes Labels'
- For maximum intensity in the heat map, I set it to the highest humidity found in the data set

Three observable trends in 'Part-I' (WeatherPy) of my assignment, basded on the data are:
1. The higher the latitude is, the lower the temperature gets exponentially, and vice versa.
2. The higher the latitude is, the lower the humidity gets exponentially, and vice versa.
3. The percentage of cloudiness is scattered almost evenly with both, higher and lower latitude.