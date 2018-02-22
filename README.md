## Unit 6 | Assignment - What's the Weather Like?

Skills Tested: Python programming, API calls, Array/Dictionary data search, data analysis/visualization via Pandas and Matplotlib

This program utilizes the OWM api service to locate weather data for a city that is entered into it's search parameters.  The program calls citipy, which is another module written by WingChen, which uses a kdtree to locate the nearest city to a given coordinate.  The program then stores the city name and country as a tuple into a list (list of tuples).  The program then uses that list to pull information from the OWM developer api system.  Random longitude and latitude coordinates are determined by the randint function that is imported as a dependency.  Citipy is installed into PythonData, and the coordinates generated, citypy will determine the closest city.  The city and country is stored into a list, where it will be used to find the weather condition via API calls to OWM.  

After the data collection, data is visualized via Matplotlib, and graphs are exported as png.  Data analysis of the weather patterns were summarized.
