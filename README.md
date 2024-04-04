# IoTConnect-hackaton
Code for laccei hackton competition

Here are the codes developed for the solution by the IoTConnect team of students and professors from ULACIT, Costa Rica. The implementation involves using a turbidity sensor to detect contaminants in water. The first code was used to test the sensor using an Arduino. After iterations with different water samples, it was determined that within a range of 0-20, the water was clean and safe to drink. From 20 to 50, it had impurities and is not recommended for consumption, and above 50, it is contaminated. In the second code, the same turbidity sensor was used, but this time connected to the ESP8266 to transmit the provided data to ThingSpeak by MathWorks. Here is the channel: https://thingspeak.com/channels/2480973

if you want to replicate this experiment, it is needed a turbity sensor, and an arduino, an esp8266 and a user in thingspeak.com to create the channel
It is advised first to install the libraries for esp8266 and thinspeak in IDE for arduino, the codes work there. 
