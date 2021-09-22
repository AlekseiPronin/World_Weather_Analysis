# World_Weather_Analysis

## The Purpose

The main goal of this project was to collect and present data which user can filter based on his preffered travel criterias in order to find the ideal hotel. 

To perform this task the Jupyter Notebook was used as well as Citipy module, the number of random latitudes and longitudes were collected, then requests were performed on OpenWeather API to get the JSON data. Later data was added to Pandas DataFrame and series of scatterplots were created using Matplotlib to show the relationship between latitudes and longitudes and variety of weather parameters. Also, statistical calculation using linear regression was performed. Finally, after data was cleaned, cities were mapped using Jupyter Gmaps and Google Places API


## Result

As a result, the series of scatterplots and maps were created. 

For example, you can see the correlation between latitude and city maximum temperature:

![Fig1](https://github.com/AlekseiPronin/World_Weather_Analysis/blob/main/weather_data/Fig1.png)


Also, cities were mapped with markers for each city containing hotel name, city, country index and weather conditions:

![WeatherPy_vacation_map](https://github.com/AlekseiPronin/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)
