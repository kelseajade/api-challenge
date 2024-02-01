# api-challenge
I used api keys from OpenWeather and Geoapify to create data frames for the following activities. These are included in my gitignore. 
Part 1: WeatherPy
I created a Python script to visualize the weather of over 500 cities of varying distances from the equator. I recieved my data from the the OpenWeatherMap APILinks.

The code required to generate random geographic coordinates and the nearest city to each latitude and longitude combination was provided.
I created scatter plots similar to the ones done in class for the following Latitude vs. Humidity, Latitude vs. Cloudiness, and Latitude vs. Wind Speed. These scatter plots were saved as output figures. These figures are included in the output_data file as well as the csv used. 

To find the Linear Regression for Each Relationship listed I used the Learning Assistant to find how to define a function rather than the way we used in class. There were similarities in the equation but the variables were more complex.

I created the following plots:

Northern Hemisphere: Temperature vs. Latitude

Southern Hemisphere: Temperature vs. Latitude

Northern Hemisphere: Humidity vs. Latitude

Southern Hemisphere: Humidity vs. Latitude

Northern Hemisphere: Cloudiness vs. Latitude

Southern Hemisphere: Cloudiness vs. Latitude

Northern Hemisphere: Wind Speed vs. Latitude

Southern Hemisphere: Wind Speed vs. Latitude

After each pair of plots, I discussed the difference in relationships between the southern and northern hemisphere that the linear regression is modeling. 

Part 2: VacationPy
The city data frame from the WeatherPy activity is used to find cities with comfortable weather. I created a map that displays a point for every city in the city_data_df DataFrame. The size of the point is the humidity in each city. The conditions included a max temperature lower than 27 degrees but higher than 21, wind speed less than 4.5 m/s, and zero cloudiness. After that hotels within 10,000 meters were searched. I kept getting no hotels found and recieved help from the instructor and TA. I had to change the temperature from imperial to metric.


