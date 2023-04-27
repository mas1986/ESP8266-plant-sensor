# ESP8266-plant-sensor

This is propotype project for ESP8266 microcontroller + DHT22 humidity and temp sensor + Soil humidity capacitive sensor.

General architecture:

ESP8266 is connected with DHT22 and capacitive sensor.
ESP8266 sends events to Azure IOTHub.
Azure IOTHub then sends the requests to ???? and data finally is stored in Table storage.
To read the sensors data it can be used Azure functions app that provide data from storage.
Finally data can be viewed via web application (to be added to github)

ToDo:
- Detailed documentation
- Flow of data
- infrastructure as a code
