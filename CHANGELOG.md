## 0.1.0

* Added start and pause cleaning
* Added return to base
* Added enable and disable schedule
* Added enable and disable eco mode
* Added battery info

## 0.2.0

* Added dock info
* Improved logging to use a debug library

## 0.2.1

* Improved the go to dock command

## 0.3.0

* Added periodic refresh of robot state while cleaning
* Added optional periodic refresh of robot state while not cleaning
* Added error messages when cant login or get robot
* Improved go to dock switch to be enabled as soon as possible without manual refresh
* Improved switches to indicate the time an action needs to complete
* Improved eco mode to not be overwritten by robot state update

## 0.3.1

* Added support for Neato BotVac D5 Connected

## 0.3.2

* Fixed a bug that refresh is not disabled when set to 0

## 0.4.0

* Added support for multiple robots
* Added log output when user requests accessory identify
* Changed plugin to platform instead of single accessory
* Removed parameter name from config

## 0.4.1

* Added config parameter for extraCareNavigation

## 0.4.2

* Added config parameter to disable switches/sensors

## 0.4.4

* Fixed config parameter to disable switches/sensors not optional

## 0.4.5

* Fixed compatibility with homebridge 0.4.23 (occupancy sensor not working)

## 0.4.6

* Added error log while refreshing robot state
* Fixed a rare bug where the robot stops after some seconds of cleaning