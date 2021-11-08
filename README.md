# World_Weather_Analysis


## Overview 
To better provide real-time suggestions for PlanMyTrip client's ideal hotels (refering to their ideal weather conditions and city locations), a series of scripts were written to accompish:
- Collect and analyze weather data across cities worldwide 
    -  Use NumPy module to generate 2,000 randomized continental latitudes and longitude pairs 
    - Use CityPy module to list nearest cities
    - Use OpenWeatherMap API to request the current weather data from each unique city
    - Create a pandas dataframe with city and weather data
<img width="842" alt="Screen Shot 2021-11-07 at 10 02 06 PM" src="https://user-images.githubusercontent.com/91163155/140682440-164c44fd-9067-449d-a760-3cd8a9707de3.png">


- Utalize client input boxes such that PlanMyTrip will be able to recommend ideal hotels based on clients' weather preferences.
    - Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
    - Create a heatmap for the new DataFrame.
    - Find a hotel from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature.
    - Store the name of the first hotel in the DataFrame.
    - Add pop-up markers to the heatmap that display information about the city, current maximum temperature, and a hotel in the city.<img width="1026" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/91163155/140682495-0f20fe34-56ef-48d7-b242-0bea2a190e86.png">

    
- Create a feature that will allow beta tester to choose four cities and create a travel itinerary. 
    - Use the Google Maps Directions API, create a travel route between the four cities as well as a marker layer map.
<img width="882" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/91163155/140682507-ade0d742-a4f8-4230-8c56-ee31154d324b.png">
<img width="879" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/91163155/140682509-b489125f-1499-4b07-93a0-91bfd0a87267.png">

## Resouces
- Data Souce: OpenWatherMap API, Google Maps, Places, and Maps API 
- Software: Python 3.8.8, Visual Studio Code 1.60.2 (With Jupyer Extension)








