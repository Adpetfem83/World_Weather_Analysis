# World_Weather_Analysis


## Overview

This analysis looks at different weather patterns around the global and offers insights to travelers who want to book a trip. There are three folders here that offer different levels of analysis: weather database, vacation search, and vacation itinerary.

### Weather Database

This folder uses Open Weather Map API to pull weather information on different cities around the world. That information consists of:

1. Maximum Temperature
2. Cloudiness
3. Wind Speed
4. Humidity
5. Current Weather Description


![Weather_Database](https://github.com/Adpetfem83/World_Weather_Analysis/blob/main/Weather_Database/Weather_Data.PNG)


These different categories of information make it easy for travelers to choose exactly what they are looking for in a travel destination.



### Vacation Search

This folder takes the information gained in the weather database and uses Google Maps API to plot different travel destinations with a hotel at each location. For example, the image below shows the locations of all the places in the database that have a daily maximum temperature between 50 and 90 degrees farinheit.


![vacation_search_map](https://github.com/Adpetfem83/World_Weather_Analysis/blob/main/Vacation_Search/clean_hotel_df.png)






![vacation_search_map](https://github.com/Adpetfem83/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

### Vacation Itinerary




This folder takes the search information from the search folder and uses Google Maps directions API to create a vacation itinerary. For example, the image below shows a 4 stop itinerary in Northern California that features Fortuna, Guererro Negro, Dodge City, and Havelock.


![vacation_itinerary_map](https://github.com/Adpetfem83/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)
Also, as with the vacation search folder, there is a hotel at each location.






![vacation_itinerary_markers](https://github.com/Adpetfem83/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)



