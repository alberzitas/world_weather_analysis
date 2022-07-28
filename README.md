# World Weather Analysis

## Purpose and Overview

The purpose of this project is to collect and present data for customers of PlanMyTrip to find the best hotel anywhere. To do this, we used Jupyter Notebook, MatPlotlib, and API calls to create a series of maps to describe the best itinerary for them.

## Analysis

The first step was to create a map of all the cities that fall into the range of preferred temperatures of the customers. To do that, we performed an API call and mapped all the hotels that were located within the preferred temperature range. 
![](Vacation_Search/WeatherPy_vacation_map.png)

Next, we found 4 cities that matched the customers' preferrences and created an itinerary for them using the same map that we had generated for the previous step. This time however, we created a route from each city to the next, highlighting a suggested path for the customers to take.
![](Vacation_Itinerary/WeatherPy_travel_map.png)

Finally, the names of the hotels and the cities on the itinerary are put on display for each location
![](Vacation_Itinerary/WeatherPy_travel_map_markers.png)
