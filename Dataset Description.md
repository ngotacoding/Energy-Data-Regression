# Dataset Description

  ## Appliances Energy Prediction Dataset
The data set captures energy consumption of appliances in a house over a period of 4.5 months with a sampling frequency of 10 minutes. The temperature and humidity conditions inside the house were monitored using a ZigBee wireless sensor network, and the energy data was logged using m-bus energy meters.

The dataset includes the following information:

- Temperature and humidity readings from the wireless sensor network (averaged over 10-minute periods).
- Energy consumption measurements logged every 10 minutes.
- Weather data obtained from Chievres Airport, Belgium (nearest airport weather station), downloaded from Reliable Prognosis (rp5.ru).
- Two random variables included for testing regression models and filtering out non-predictive attributes.


## Attribute Information:
|feature|description|
|--|--|
|Date|time year-month-day hour:minute:second|
|Appliances| energy use in Wh|
|lights | energy use of light fixtures in the house in Wh|
|T1| Temperature in kitchen area, in Celsius|
|RH_1| Humidity in kitchen area, in %|
|T2| Temperature in living room area, in Celsius|
|RH_2| Humidity in living room area, in %|
|T3| Temperature in laundry room area|
|RH_3| Humidity in laundry room area, in %|
|T4| Temperature in office room, in Celsius|
|RH_4| Humidity in office room, in %|
|T5| Temperature in bathroom, in Celsius|
|RH_5| Humidity in bathroom, in %|
|T6| Temperature outside the building (north side), in Celsius|
|RH_6| Humidity outside the building (north side), in %|
|T7| Temperature in ironing room , in Celsius|
|RH_7| Humidity in ironing room, in %|
|T8| Temperature in teenager room 2, in Celsius|
|RH_8| Humidity in teenager room 2, in %|
|T9| Temperature in parents room, in Celsius|
|RH_9| Humidity in parents room, in %|
|To| Temperature outside (from Chievres weather station), in Celsius|
|Press_mm_hg|Pressure (from Chievres weather station), in mm Hg|
|RH_out| Humidity outside (from Chievres weather station), in %|
|Windspeed | Wind speed (from Chievres weather station), in m/s|
|Visibility | Visibility  (from Chievres weather station), in km|
|Tdewpoint | Tdewpoint (from Chievres weather station), Â°C|
|rv1 | Random variable 1, nondimensional|
|rv2 | Random variable 2, nondimensional|