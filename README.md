# Internet of Things and Our Schools Environments                                                                             
## Description
This project is designed and developed for the use in STEM. 

This project, aligned with the [Curriculum](https://www.gov.uk/national-curriculum) and Engineering Habits of Mind  [(EHoM)](https://www.raeng.org.uk/publications/reports/thinking-like-an-engineer-implications-full-report), allows teachers and students to: gather data from sensors in a school environment; examine and analyse the data in their school’s computer laboratories and social spaces using the internet and Microbits; and programme actuators to react to the data.  

Activities include: selecting and constructing sensor networks to suit environmental problems; examining data sets; negotiating team roles for installing and coding; testing hardware; working scientifically through enquiry and dialogue across STEM subject areas; and examining industrial, scientific and medical [grand challenges](https://www.gov.uk/government/publications/industrial-strategy-the-grand-challenges/industrial-strategy-the-grand-challenges)

## Research 

### Envrionmental IoT

 * Why do we need to sense the world around us with devices that are connected in a network?
 * Schools are part of a [smart city](), a city that uses sensors, big data and interconnected devices in the 10000s. It is important that the schools adopt this method early by using the sensors and big data as a learning tool for those in education so to prepare them for a digital world. 

## Components
Name            | Image
------------    | -------------
NodeMcu         | ![](https://circuits4you.com/wp-content/uploads/2018/02/NodeMCU.jpg)
DHT11/22        | ![](http://www.uugear.com/wordpress/wp-content/uploads/2015/03/dht11_2-300x300.jpg)
Microhone Sensor| ![](https://sites.google.com/site/summerfuelrobots/_/rsrc/1374684958016/arduino-sensor-tutorials/arduino-sound-sensor/arduino-sound-sensor-module-sound-detection-module-201211270080030_fheiji1354280389445.jpg?height=320&width=320)

## Installation

### Software
* Video link - > coming soon!

* First you will need to create a ThingSpeak account - https://thingspeak.com/users/sign_up - free or any other option if you are willing to pay. 

* You'll also need to download Arduino IDE - https://www.arduino.cc/en/Main/Software - you can make a donation if you like, but it is free to use. 

Once downloaded you will need to install the following libraries:

* ThingSpeak
* DHT sensor library for ESPx

You'll need to add support for NodeMCU in Arduino IDE
* Preferences -> Additional boards manager url -> http://arduino.esp8266.com/stable/package_esp8266com_index.json

### Hardware
Name            | Image
------------    | -------------
NodeMcu pinout         | ![](https://raw.githubusercontent.com/CompEng0001/BeeSensors_STEM/master/Media/NodeMCU_pinout.png)

## Usage
Once installed this is how it works and how you can access the data etc.

## Contribution
Author: [CompEng0001](https://github.com/CompEng0001)
Contributor: [Phil Moffitt](https://github.com/philipgmoffitt)

## Licensing 
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

* Libraries
    * ThingSpeak -> [MIT]()
    * DHT Sensor library for ESPx ->  [GNU GENERAL PUBLIC LICENSE 2007](http://fsf.org/)

