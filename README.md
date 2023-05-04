# Python-api_challenge

## Instructions

This activity is broken down into two parts, WeatherPy and VacationPy.

## Part 1: WeatherPy

Create a Python script to visualize the weather of over 500 cities of varying distances from the equator.
Use ## citipy Python library and ## OpenWeatherMap API Links, to create a representative model of weather across cities.
Use the WeatherPy.ipynb Jupyter notebook provided. With the starter code develop a solution to address the required functionalities.

## Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude

With OpenWeatherMap API retrieve the weather data from the cities list generated in the starter code to create a series of scatter plots to showcase the following relationships:

  - Latitude vs. Temperature
  
  - Latitude vs. Humidity
  
  - Latitude vs. Cloudiness
  
  - Latitude vs. Wind Speed
  
## Requirement 2: Compute Linear Regression for Each Relationship

Next compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).
Then create a series of scatter plots. Include the linear regression line, the model's formula, and the r values.
Sample scatter plot with the linear regression line.

- You should create the following plots:

    - Northern Hemisphere: Temperature vs. Latitude
    
    - Southern Hemisphere: Temperature vs. Latitude
    
    - Northern Hemisphere: Humidity vs. Latitude
    
    - Southern Hemisphere: Humidity vs. Latitude
    
    - Northern Hemisphere: Cloudiness vs. Latitude
    
    - Southern Hemisphere: Cloudiness vs. Latitude
    
    - Northern Hemisphere: Wind Speed vs. Latitude
   
   - Southern Hemisphere: Wind Speed vs. Latitude

Describe any relationships or other findings.

## Part 2: VacationPy

In this part, use your weather data skills to plan future vacations. Using Jupyter notebooks, geoViews Python library, and the Geoapify API.

The main tasks will be to use the Geoapify API and the geoViews Python library and Python skills to create map visualizations.

1) Create a map that displays a point for every city in the city_data_df DataFrame. The size of the point should be the humidity in each city.

2) Narrow down the city_data_df DataFrame to find your ideal weather condition.

3) Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

4) For each city, use Geoapify API to find the first hotel located within 10,000 meters of your coordinates.

5) Add the hotel name and the country as additional information in the hover message for each city on the map.
