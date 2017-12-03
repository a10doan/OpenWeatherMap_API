## Unit 6 | Assignment - What's the Weather Like?



This program utilizes the OWM api service to locate weather data for a city that is entered into it's search parameters.  The program calls
citipy, which is another module written by WingChen, which uses a kdtree to locate the nearest city to a given coordinate.  The program then 
stores the city name and country as a tuple into a list (list of tuples).  The program then uses that list to pull information from the OWM developer 
api system.