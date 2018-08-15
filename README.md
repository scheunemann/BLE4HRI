# BLE4HRI #

## Gimbal (beacons) ##
We used Gimbal simply because they are affordable and small. Any other iBeacon will be acceptable. 

We do not use the Gimbal Beacon protocol since the UUID get changed each start up.

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
- comment the script

## Publication ##
M. M. Scheunemann, K. Dautenhahn, M. Salem and B. Robins, "Utilizing Bluetooth Low Energy to recognize proximity, touch and humans," In *2016 25th IEEE International Symposium on Robot and Human Interactive Communication (RO-MAN)*, pages 362--367, IEEE, New York, NY, 2016.
https://doi.org/10.1109/ROMAN.2016.7745156

keywords: {recognize proximity;humans;human inhabited environment;adaptive behavior;cost intensive task;inexpensive bluetooth low energy;BLE devices;configurable technique;noisy laboratory setting;mobile spherical robots;proximity information;touch sensor;raw received signal strength;RSS;sensor system;human-robot interaction;HRI experiments;Bluetooth;Cameras;Robot vision systems;Mobile robots;Tactile sensors}


## License ##
This project is licensed under the terms of the MIT license.
