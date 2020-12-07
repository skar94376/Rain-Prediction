# Predicting rain in Australia
 

The dataset contains daily weather observations from numerous Australian weather stations from Jan-2008 to August 2017. Observations of the climate data were drawn from numerous weather stations of the country.
There are total 23 features:

**Categorical Features**
- Date: The date of observation 
- Location: location of the weather station
- RainToday: 1 if precipitation in 24 hours exceeds 1mm, otherwise 0
- WindDir3pm: Direction of the wind at 3pm 
- WindDir9am: Direction of the wind at 9am 
- WindGustDir: The direction of the strongest wind gust of the day

**Numerical Features**
- MinTemp: The minimum temperature of the day in degrees celsius
- MaxTemp: The maximum temperature of the day in degrees celsius
- Rainfall: The amount of rainfall recorded for the day in mm 
- Evaporation: evaporation (mm) in the day
- Sunshine: The number of hours of bright sunshine in the day.
- WindGustSpeed: The speed (km/h) of the strongest wind gust of the day
- WindSpeed9am: Wind speed (km/hr) averaged over 10 minutes prior to 9am
- WindSpeed3pm: Wind speed (km/hr) averaged over 10 minutes prior to 3pm
- Humidity9am: Humidity (percent) at 9am
- Humidity3pm: Humidity (percent) at 3pm
- Pressure9am: Atmospheric pressure (hpa) reduced to mean sea level at 9am
- Pressure3pm: Atmospheric pressure (hpa) reduced to mean sea level at 3pm
- Cloud9am: Fraction of sky obscured by cloud at 9am. This is measured in "oktas". A 0 measure indicates completely clear sky whilst an 8 indicates that it is completely overcast.
- Cloud3pm: Fraction of sky obscured by cloud (in "oktas") at 3pm. A 0 measure indicates completely clear sky whilst an 8 indicates that it is completely overcast. 
- Temp9am: Temperature (degrees C) at 9am
- Temp3pm: Temperature (degrees C) at 3pm

**Target Variable**
- RainTomorrow: The target variable. Will it rain tomorrow? (1 = yes, 0 = no )
***
