# CIS600 Internet of Things: Application Development

# Spring 2023 - Assignment 2
# Cloud-Based IoT System
This project is a cloud-based IoT system that collects data from virtual sensors using the MQTT protocol and displays. The virtual sensors generate random values for temperature, humidity, CO2 sensor, rain height, wind direction, and wind intensity, which are published on an MQTT channel. The cloud-based IoT backend uses the ThingsBoard platform to store the sensor data, and to display the data received during the last five hours and the latest sensor data values.

Table of Contents
* Prerequisites
* Getting Started
* Usage
<h2>Prerequisites</h2>
To run this project, you will need:

* Python 3.x
* pip package manager
* ThingsBoard account (demo account can be created for free)

</h2>Getting Started</h2>
Install paho mqtt first and then run the python script. Before running first set up the demo thingboard by going to the thingsboard demo site add devices and copy the access token and replace it to the ACCESS_TOKEN, then create dashboard for both the environment and add the widgets which will point to this device and display respective environment sensors.

<h2>Usages</h2>
Displays the latest sensor data values received from all the sensors of a specified environmental station. We can view the last five hurs data by selecting timeline window to show last five hours data.


