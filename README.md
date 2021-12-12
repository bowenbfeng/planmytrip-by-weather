# PlanMyTrip by Weather

## Purpose of this project

> Jack loves the PlanMyTrip app. Beta testers love it too. And, as with any new product, they’ve recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data you’ve already retrieved in this module. Then, you'll have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, you will create a travel route between the four cities as well as a marker layer map.

## Feature update

### Real-time temperature with OpenWeatherMap API

With the use of OpenWeatherMap API, the Weather_Database file will retrieve the real-time weather condition of the cities. 

### Vacation search by temperature

With the use of Google Maps API, the Vacation_Search file will shows a list of destinations, of which the temperature is within the range inputted. Markers have also been created to be shown on the map. Below is an example. 

![](/Vacation_Search/WeatherPy_vacation_map.png)

### Itinerary creation with Google Maps API

With the use of Google Maps API, the Vacation_Itinerary file will create the route between the start location and the end location, with support of multiple waypoints. Below is an example. 

![](/Vacation_Itinerary/WeatherPy_travel_map.png)

In addition, markers have been created for all the stops. Below is an example. 

![](/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
