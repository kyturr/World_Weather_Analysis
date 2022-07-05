# World_Weather_Analysis

## Overview of the Analysis
The purpose of this analysis was to create random city data gathering from online weather databases in order to find trends in various weather conditions in relation to the location's latitude. Using this data, further analysis was performed to create an application that would find and plot hotel locations that reside in cities that fit a specified weather criteria. This application was then refined to plan and plot a trip using some of the hotel locations. This project showcases experience generating randomized data to determine significant statistical trends as well as using API calls to gather data from online databases and form figures from widgets.

## Results
Collection of heat maps and marker maps generated from this project:

City Location Markers
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/103979048/177433542-bfbcd2fe-a9bb-4fd8-b72d-5c7d28b18524.png)

Heat heat map
![image](https://user-images.githubusercontent.com/103979048/177434247-df9862bf-c812-4f47-a4f8-2ab0cfe06c89.png)

Humidity heat map
![image](https://user-images.githubusercontent.com/103979048/177434359-b73bc9fa-e4f5-4383-a3e5-c82602e28756.png)



## Summary
The app allows a user to input a specific range of temperatures for their ideal vacation and the app will output cities that were generated as part of the random city gathering that fit the current weather criteria. The markers using google maps API are useful visual representation and will also give basic information about the city locations. For many of the ideal temperature ranges most locations were along coastal regions. This could be because of hyper sampling in the coasts because about 70% of the randomly generated coordinates would land in some form of water and thus the closest city would be a coastal city. This would explain why even increasing the random locations sampled to 2000 there were still only about 750 unique cities to choose from. However, there is precedent for coastal cities having nicer weather so the findings are in line with those notions. Additionally since all the data is instantaneous, the weather around the world may differ because of day/night conditions.

To improve the app for trip planning, an index number could be added to the markers and user input could be used to select the stops based on the index numbers that they input. This will be much more flexible than hard coding in each stop. The prompt can ask if there is an additional stop and then ask to input the index, then the input can go into the stop variables and this can run in a while loop to get the stops until the user inputs “No” for additional stops. 
