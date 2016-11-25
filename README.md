# BLE4HRI #

## Gimbal (beacons) ##
We used Gimbal simply because they are affordable and small. Any other iBeacon will be acceptable. 

We do not use the GimbalBeacon protocol since the UUID get changed each start up.

Example configuration:

| Name        | Setting           |
| -------------- |------------------|
| Configuration type      | iBeacon |
| Proximity UUID           | 444444...4444 |
| Major | [1..X] _(ID of a person)_ |
| Minor |  0 _(not used)_|
| Measured Power | Recommended |
| Transmission Interval (MS) | 100 _(maximum value)_|


## BLED112 (central device) ##

[API Reference Manual V1.3](http://www.silabs.com/Support%20Documents/RegisteredDocs/Bluetooth_Smart_Software-BLE-1.3-API-RM.pdf)

[BGScript Scripting Language](https://www.silabs.com/Support%20Documents/RegisteredDocs/UG209.pdf)

## ToDo ##
- use a custom characteristic rather then exploit the heart rate
- comment the script
