WEATHERPY AND VACATIONPY CHALLENGE
1. Project Overview and Purpose:
This exercise will offer two key resources for the user: (a) a visualization of weather data for over 500 cities at various distances from the equator [referred to as "WeatherPy"], and (b) information such as city names and weather characteristics to assist in planning future vacations [referred to as "VacationPy"].
2. Dataset Description: 
Data for the WeatherPy component was partially retrieved from OpenWeather [api.openweathermap.org/] via an Application Programming Interface (API), yielding a JavaScript Object Notation (JSON) file after processing the API response. Additional data was sourced from a .csv file named "cities.csv," located in the output_data folder. This file includes information on location (city identifier, city name, and country), geographical coordinates (latitude and longitude), and weather details (maximum temperature, humidity, cloudiness, wind speeds, and date). Data for the VacationPy component was obtained from Geoapify [api.geoapify.com/] via API, also resulting in a JSON file after processing the API response, and was supplemented with information from the "cities.csv" file.
3. Data Cleaning and Preprocessing:
The API responses were already clean and were transformed into JSON format. The API responses were generated from specific data requests to each website and were visualized in DataFrames to assess their completeness and accuracy.
4. Data Visualization Techniques and result
For WeatherPy, scatter plots were created both with and without linear regression. For VacationPy, maps were generated.
5. Results and Analysis: 
(a) For WeatherPy, the following plots were produced: 
-	Maximum Temperature vs. Latitude:
![image](<output_data/Max Temperature vs. Latitude.png>)