# World_Weather_Analysis
Using weather data, this project can be used to help determine the best vacation destinations for interested travelers.

The first step was to pull the current weather data around the globe. Weather_Database.ipynb uses openweathermap.org's API to generate the current weather data for a series of 680 differnt cities world-wide.  A database was created to create each city's temperature, humidity, cloudiness, wind spead and current weather description.

Using the database in step one, a quick prompt was created to ask the user what the minimum and maximum temperature was preferred for a trip.  From that, a list of cities that fit the criterea is generated to create a new DataFrame for the customer to look through.  This could be further nerrowed down by country if desired.

The final step was to create an initial marker map of the world of these cities so the user could narrow down where they wish to vacation, and create a final mmap with an itenerary of four different cities that could be visited within driving distance.
