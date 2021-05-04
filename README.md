# Python-API-Challenge
The WeatherPy directory contains these files:

	* WeatherPy.ipynb	
	* output_data directory which contains one csv file and four png files
	* api_keys.py

The WeatherPy jupyter notebook file contains weather analysis on a random list of cities. The analysis steps are shown below.

	1: Generate a random list of unique cities around the world using random latitude and longitudes and finding the closest cities.
	
	2: Use a weather api to import weather data on all cities. Save this to a dataframe and output to csv file.
	
	3: Create a series of scatter plots to showcase the following relationships. Additionally, save a png output image of each plot.
		* Temperature (F) vs. Latitude
		* Humidity (%) vs. Latitude
		* Cloudiness (%) vs. Latitude
		* Wind Speed (mph) vs. Latitude
	
	4: Run linear regression on each relationship, separating them into Northern Hemisphere and Southern Hemisphere.
		* Northern Hemisphere - Temperature (F) vs. Latitude
		* Southern Hemisphere - Temperature (F) vs. Latitude
		* Northern Hemisphere - Humidity (%) vs. Latitude
		* Southern Hemisphere - Humidity (%) vs. Latitude
		* Northern Hemisphere - Cloudiness (%) vs. Latitude
		* Southern Hemisphere - Cloudiness (%) vs. Latitude
		* Northern Hemisphere - Wind Speed (mph) vs. Latitude
		* Southern Hemisphere - Wind Speed (mph) vs. Latitude


The VacationPy directory contains these files:

	* VacationPy.ipynb
	* api_keys.py

The VacationPy jupyter notebook file contains gmaps plots from the weather data imported from the WeatherPy notebook.

	1: Create a heat map that displays the humidity for every city from the WeatherPy notebook.
	
	2: Narrow down the DataFrame to find your ideal weather condition.
		* A max temperature lower than 80 degrees but higher than 70.
		* Wind speed less than 10 mph.
		* Zero cloudiness.
	
	3: Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.
	
	4: Plot the hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.