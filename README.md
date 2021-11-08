# World_Weather_Analysis


## Overview 
To better provide real-time suggestions for PlanMyTrip client's ideal hotels (refering to their ideal weather conditions and city locations), a series of scripts were written to accompish:
- Collect and analyze weather data across cities worldwide 
    -  Use NumPy module to generate 2,000 randomized continental latitudes and longitude pairs 
    - Use CityPy module to list nearest cities
    - Use OpenWeatherMap API to request the current weather data from each unique city
    - Create a pandas dataframe with city and weather data

- Utalize client input boxes such that PlanMyTrip will be able to recommend ideal hotels based on clients' weather preferences.
    - Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
    - Create a heatmap for the new DataFrame.
    - Find a hotel from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature.
    - Store the name of the first hotel in the DataFrame.
    - Add pop-up markers to the heatmap that display information about the city, current maximum temperature, and a hotel in the city.
- Create a feature that will allow beta tester to choose four cities and create a travel itinerary. 
    - Use the Google Maps Directions API, create a travel route between the four cities as well as a marker layer map.

## Resouces
- Data Souce: OpenWatherMap API, Google Maps, Places, and Maps API 
- Software: Python 3.8.8, Visual Studio Code 1.60.2 (With Jupyer Extension)








