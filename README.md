# Weather Data Visualizataion using APIs

## Weather Data Visualizataion using APIsOverview

This project is to perform exploratory data analysis on approximately 2000 random lattitudes and longitudes for a hypothetical travel company leveraging: 
* analysis skills including retrieving data from APIs via "get" requests, writing python functions
* visualizations
* statistical skills
* creating data series and data frames. 


### Objective 1: Retrieve Weather Data
1. Retrieve all of the following information from the OpenWeatherMap API
 * Latitude and longitude
 * Maximum temperature
 * Percent humidity
 * Percent cloudiness
 * Wind speed
 * Weather description
2. Add the weather data to a new DataFrame
3. Export the DataFrame to a .csv file

### Objective 2: Create a Customer Travel Destinations Map
1. Use input statements to receive customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels.
 * Prompt for the preferred minimum and maximum temperatures
 * Create a new vacation DataFrame based on the minimum and maximum temperature entered, and empty rows are dropped
 * Export the vacation DataFrame of the preferred temperature range locations and nearby hotels to a .csv file
2. Show those vacation destinations on a marker layer map with pop-up markers for cities. The pop up markers include the following information:
 * Hotel name
 * City
 * Country
 * Maximum temperature
 * Current weather description
3. Marker layer map image is saved

### Objective 3: Create a Travel Intinery Map
1. Using the Google Directions API, create a travel itinerary that shows the route between four cities chosen out of the vacation set of destinations. 
 * Create four DataFrames, one for each city on the itinerary
 * Retrieve the latitudes and longitudes for each of the four cities
 * Create a direction layer map between the cities and the travel map
 * Save an image of the map
3. Create a marker map with a pop-up markers for each city on the itinerary. Each marker has the following information:
 * Hotel name
 * City
 * Country
 * Maximum temperature
 * Current weather description

### Resources
- Software: Python 3.6.1, Jupyter Notebook, Pandas

## Analysis Results for Weather and Vacation Analysis
1. Retrieved all of the following information from the OpenWeatherMap API
 * Latitude and longitude
 * Maximum temperature
 * Percent humidity
 * Percent cloudiness
 * Wind speed
 * Weather description
 

A sample of these result is shown here:

![Weather Database DF image](/Weather_Database/Weather_Database_DF.png)



## Weather, Vacation, and Itinerary Visualization Summary and Proposed Recommendations
1. ...
2. 


### References:
* numpy.random.uniform(): https://docs.scipy.org/doc/numpy-1.14.0/reference/generated/numpy.random.uniform.html
* citipy: https://pypi.org/project/citipy/
* GitHub citipy repository: https://github.com/wingchen/citipy
* OpenWeatherMap website: https://openweathermap.org/api
* Requests: HTTP for Humans: https://requests.kennethreitz.org/en/master/
* Requests Library quickstart: https://requests.kennethreitz.org/en/master/user/quickstart/#make-a-request
* OpenWeatherMap API for current weater: https://openweathermap.org/current
* units section of the current weather data page: https://openweathermap.org/current#data
* add the Chrome JSONView extension: https://chrome.google.com/webstore/detail/jsonview/chklaanhfefbnpoihckbnefhakgolnmc
* datetime: https://docs.python.org/3.7/library/datetime.html
* strftime(): https://docs.python.org/3.7/library/datetime.html#strftime-and-strptime-behavior
* errors and exceptions: https://docs.python.org/3.7/tutorial/errors.html
* time module: https://docs.python.org/3.6/library/time.html#functions
* linear regression: https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.linregress.html#scipy.stats.linregress
* Google Maps Platform: https://cloud.google.com/maps-platform/
* Places API Usage and Billing https://developers.google.com/places/web-service/usage-and-billing
* gmaps dependency: https://jupyter-gmaps.readthedocs.io/en/latest/tutorial.html
* gmaps error messages: https://developers.google.com/maps/documentation/javascript/error-messages?utm_source=maps_js&utm_medium=degraded&utm_campaign=keyless#api-key-and-billing-errors
* Nearby Search requests: https://developers.google.com/places/web-service/search#PlaceSearchRequests%0D%0A
* PlaceTypes guide: https://developers.google.com/places/web-service/supported_types
* Nearby Search: https://developers.google.com/places/web-service/search#PlaceSearchRequests
* gmaps how to add markers: https://jupyter-gmaps.readthedocs.io/en/latest/tutorial.html#markers-and-symbols
 
