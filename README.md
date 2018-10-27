# dz-solarData
dzEvent Script for Solar Data computation based on Dark Sky API

Configuration needed for the scripts to works properly :

- idxSolarAzimuth : Create a virtual device "Custom Sensor", axis = "degrees" and get its id
- idxSolarAltitude : Create a virtual device "Custom Sensor", axis = "degrees" and get its id
- dsAPIkey : Create an account on Dark Sky and get your API Key
- latitude : Latitude of your location (can be found in DZ Settings)
- longitude : Longitude of your location (can be found in DZ Settings)
- altitude : Altitude of your location (can be found from coordinates on https://www.advancedconverter.com/map-tools/find-altitude-by-coordinates)

Optional Configuration :
- city : Name of your city (Only used for logging purpose)
- countryCode : Country Code  (Only used for logging purpose)
- idxPressure : Device ID of your Pressure Device if you have one. Not striclty needed since the script take the Dark Sky value by default
- idxLux : Create a virtual device "Lux" and get its id if you want to see the computed value of the script
- idxCloudCover : Create a virtual device "Percentage" and get its id if you want to see the computed value of the script

After the configuration is done, you can save the script as a dzEvent / Timer script in DZ.

References :

http://www.domoticz.com/wiki/Real-time_solar_data_without_any_hardware_sensor_:_azimuth,_Altitude,_Lux_sensor...

http://www.domoticz.com/forum/viewtopic.php?f=72&t=19220
