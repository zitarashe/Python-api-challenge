# Python-api-challenge

Data's true power is its ability to definitively answer questions. 
"What is the weather like as we approach the equator?"
Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?


WeatherPy
I created a Python script to visualise the weather of over 500 cities of varying distances from the equator and a Python script to visualise the weather of over 500 cities of varying distances from the equator.

Create Plots to Showcase the Relationship Between Weather Variable and Latitude

I used the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Then created a series of scatter plots to showcase the following relationships:
* Latitude vs. Temperature
* Latitude vs. Humidity
* Latitude vs. Cloudiness
* Latitude vs. Wind Speed

Compute Linear Regression for each Relationship
I had to compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).

Next, create a series of scatter plots and include the linear regression line, the model's formula, and the r values .

I created the following plots:
* Northern Hemisphere: Temperature (C) vs. Latitude
* Southern Hemisphere: Temperature (C) vs. Latitude
* Northern Hemisphere: Humidity (%) vs. Latitude
* Southern Hemisphere: Humidity (%) vs. Latitude
* Northern Hemisphere: Cloudiness (%) vs. Latitude
* Southern Hemisphere: Cloudiness (%) vs. Latitude
* Northern Hemisphere: Wind Speed (m/s) vs. Latitude
* Southern Hemisphere: Wind Speed (m/s) vs. Latitude

VacationPy
I used my  weather data skills to plan future vacations. Also, Jupyter notebooks, the geoViews Python library, and the Geoapify API.

I managed to use the Geoapify API and the geoViews Python library and employ my Python skills to create map visualisations.

Steps:
- Created a map that displays a point for every city in the city_data_df DataFrame with the size of the point being the humidity in each city.
Narrowing down the city_data_df DataFrame to find my ideal weather condition. 



