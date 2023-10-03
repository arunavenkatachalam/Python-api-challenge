# Python api challenge

Weatherpy

1. Setup the dependies. Import the citypy library. Create a empty list and set random latitude and longitude combinations. Identify nearest city for each latitude,longitude  combination. Print the number of cities in the list.

2. Create Plots to Showcase the Relationship Between Weather Variables and Latitude. Set the base url and create a dataframe to store the values City, Lat, Lng, Max Temp, Humidity, Cloudiness, Wind Speed, Country, Date. 

3. Store the dataframe in the output data in csv file. 

4. Create the Scatter Plots 
 	a. Northern Hemisphere: Temperature vs. Latitude
	b. Southern Hemisphere: Temperature vs. Latitude
	c. Northern Hemisphere: Humidity vs. Latitude
	d. Southern Hemisphere: Humidity vs. Latitude
	e. Northern Hemisphere: Cloudiness vs. Latitude
	f. Southern Hemisphere: Cloudiness vs. Latitude
	g. Northern Hemisphere: Wind Speed vs. Latitude
	h. Southern Hemisphere: Wind Speed vs. Latitude

5. Create linear regression model for all the scatter plots and explained the observation.

Vacationpy

1. Use the output data from the Weatherpy to plot a map that displays a point for every city in the city_data_df DataFrame. The size of the point should be the humidity in each city. I have commented out this portion as it works in the google collab.

2. Narrow down the city dataframe with few conditions and display the data in a new dataframe. Add hotel name in the new dataframe.

3. For each city, use the Geoapify API to find the first hotel located within 10,000 metres of your coordinates.

4. Add the hotel name and the country as additional information in the hover message for each city in the map. I have commented out this portion as it works in the google collab.














