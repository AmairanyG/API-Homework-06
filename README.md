# Unit 6 | Assignment - What's the Weather Like?

## Background

Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. So let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"

Now, we know what you may be thinking: _"Duh. It gets hotter..."_

But, if pressed, how would you **prove** it?

![Equator](Images/equatorsign.png)


## WeatherPy

In this example, a Python script was created to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I utilized a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), and a little common sense to create a representative model of weather across world cities.

To answer the above question a series of relational scatter plots were built: 

1. Temperature (F) vs. Latitude
![TempVsLat](Images/latitude_vs_temperature.png)


2. Humidity (%) vs. Latitude
![HumidityVsLat](Images/latitude_vs_humidity.png)


3. Cloudiness (%) vs. Latitude
![CloudinessVsLat](Images/latitude_vs_cloudiness.png)


4. Wind Speed (mph) vs. Latitude
![WindSpeedVsLat](Images/latitude_vs_wind.png)



## Analysis

* Although the weather in cities closest to the equator is not necessarily the warmest, temperature is higher on cities that are closer to the equator along the latitudes of -35 and 30. 
* Wind speed tends to generally be between 0 and 20 mph regardless of latitude.
* There is no strong relationship between latitude and humidity/cloudiness/wind speed.




## Copyright

Data Boot Camp © 2018. All Rights Reserved.
