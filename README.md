# World_Weather_Analysis
## Overview of Project
The purpose of this project was to explore ways to use APIs to collect large amounts of up-to-date data about possible vacation destinations throughout the world.
First, a large set of random numbers was generated and zipped together to form latitude-longitude pairs. These pairs were then processed in an interative fashion to find the nearest sufficiently large world city to each pair.
Then, data was retrieved from Open Weather to determine the current conditions, including temperature, cloud cover, and an overall description of the weather, for each city.
From there, user input could be used to filter the results to a desired range of temperatures. With this information, a map was generated showing hotels and weather for cities that met the criteria.
Lastly, a set of cities within one country (in this case, Japan) was chosen. The Google Directions API was used to generate a travel itinerary that reached all four of the cities in the set and returned to the starting city


## Deliverables for Challenge
The finished deliverables are held in three folders within this repository.
- [Weather_database](Weather_database) holds the retrieved city names and weather data for each pair of coordinates that was generated.
- Vacation_search holds the code for searching based on a range of temperatures, and an example of the output map of hotels with informational pins.
- Vacation_itinerary holds the code for, and an example of, a travel itinerary generated from a group of four cities.
