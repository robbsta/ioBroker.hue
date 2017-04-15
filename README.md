![Logo](admin/hue.jpeg)
# ioBroker Philips Hue Bridge Adapter
==============

[![NPM version](http://img.shields.io/npm/v/iobroker.hue.svg)](https://www.npmjs.com/package/iobroker.hue)
[![Downloads](https://img.shields.io/npm/dm/iobroker.hue.svg)](https://www.npmjs.com/package/iobroker.hue)

[![NPM](https://nodei.co/npm/iobroker.hue.png?downloads=true)](https://nodei.co/npm/iobroker.hue/)

English
--------------------
Connects Philips Hue LED Bulbs, Friends of Hue LED Lamps and Stripes and other 
SmartLink capable Devices (LivingWhites, some LivingColors) via Philips Hue Bridges to ioBroker.

You must first link you HUE bridge with ioBroker. 
1. For that find first the IP address by pressing "Find Bridge" button. It is only enabled if no IP address entered.
2. After IP address is found the USER must be created. For that press the "Create User" button and then press "Link" button on HUE bridge. "Create User" button is only enabled if no USER entered

Deutsch
-------------
Bindet Philips Hue / LivingColors / LivingWhites Lampen ein. 
In den Adapter-Settings muss die IP der Hue Bridge sowie ein Username konfiguriert werden. 

## Install

## Changelog
### 0.6.2 (2017.04.15)
* (bluefox) Use new verions of npm library

### 0.6.0 (2016.11.30)
* (pmant) support new lamps
* (pmant) add light name to log

### 0.5.9 (2016.10.11)
* (pmant) fix error with null values

### 0.5.8 (2016.06.05)
* (bluefox) fix typo

### 0.5.7 (2016.06.05)
* (soef) write back known states for group/room
* (soef) Integer conversion for bri_inc command

### 0.5.6
* (Pmant) (experimental) support for power switches

### 0.5.5
* (Pmant) fix error with xy state
* (Pmant) support level in command state

### 0.5.4
* (Pman) Lightset 0 fixed
* (Pman) support for diffent gamuts
* (Pman) support Rooms (new HUE App)

### 0.5.3
* (soef) Default Lightset 0 added

### 0.5.2
* (Pman) fix jscs warnings
* (Pman) improve RGB conversion
* (Pman) add update rgb color

### 0.5.1
* (Pman) fix find bridge popup

### 0.5.0
* (Pman) update to node-hue-api 1.2.x
* (Pman) add level state (bri percentage)

### 0.4.4
* (bluefox) fix config edit

### 0.4.3
* (Pmant) fix adapter crash

### 0.4.2
* (Pmant) add find bridge (experimental)
* (Pmant) add create user (experimental)
* (Pmant) fix enable polling

### 0.4.1
* (Pmant) calculate and write back inc values

### 0.4.0
* (Pmant) add command state

### 0.3.2
* (Pmant) add groups as channels (write only)
* (Pmant) fix prevent duplicate channel names

### 0.3.1
* (Pmant) fix another bug with spaces
* (Pmant) fix hue/sat bug
* (Pmant) fix effect bug
* (Pmant) fix xy colormode

### 0.3.0
* (Pmant) fix rgb states only for color lights
* (Pmant) change set known state changes immediately
* (Pmant) change on/off sets brightness to 254/0
* (Pmant) change changing any color (hs,ct,xy) while light is off sets brightness to max
* (Pmant) fix set brightness to zero if light is off
* (Pmant) change set bri to zero if lamp is not reachable
* (Pmant) fix bridges and lamps with spaces in name

### 0.2.1
* (Pmant) add rgb states (write only)
* (Pmant) fix parent/children warnings
* (Pmant) add switch light off if brightness is zero

### 0.1.4
* (bluefox) fix some null objects

### 0.1.3
* (hobbyquaker) config UI
* (hobbyquaker) added children

### 0.1.2
* (hobbyquaker) fixes

### 0.1.1

* (hobbyquaker) fixed min/max attributes
* (hobbyquaker) added common.oper.read/write attributes

### 0.1.0

* (hobbyquaker) first release

## Roadmap/Todo

* Automatic bridge discovery
* Automatic user setup via bridge link button

## License

Apache 2.0

Copyright (c) 2017 Bluefox <dogafox@gmail.com>
Copyright (c) 2014-2016 hobbyquaker



