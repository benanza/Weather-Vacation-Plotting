# Weather/Vacation Plotting

### The Project: Visualize the weather of 500+ cities across the world of varying distance from the equator utilizing the OpenWeatherMap API.

1. Build a series of scatter plots to showcase the following relationships:

  - Temperature (F) vs. Latitude
  - Humidity (%) vs. Latitude
  - Cloudiness (%) vs. Latitude
  - Wind Speed (mph) vs. Latitude

2. Run linear regression on each relationship, separating them into Northern and Southern Hemisphere:

  - Northern Hemisphere - Temperature (F) vs. Latitude
  - Southern Hemisphere - Temperature (F) vs. Latitude
  - Northern Hemisphere - Humidity (%) vs. Latitude
  - Southern Hemisphere - Humidity (%) vs. Latitude
  - Northern Hemisphere - Cloudiness (%) vs. Latitude
  - Southern Hemisphere - Cloudiness (%) vs. Latitude
  - Northern Hemisphere - Wind Speed (mph) vs. Latitude
  - Southern Hemisphere - Wind Speed (mph) vs. Latitude

3. Randomly select and perform a weather check on at least 500 unique cities based on latitude and longitude, including a print log of each city as it's being processed with the city number and city name then save to a CSV

4. Create a heat map that displays the humidity for every city and narrow down the DataFrame to find your ideal weather condition (e.g. a max temperature lower than 80 degrees but higher than 70).

5. Using Google Places API, find the first hotel for each city located within 5000 meters of coordinates


6. Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country
