# hunterpi
Temperature control at the Hunter house pump house

I use a RapberryPi, 3 sensors (BME280 and 2x DS18B20) to measure the tmperature (and pressure and humidity). The single DS18B20 
is in the pumphouse well, and if the temperature drops below 32, i turn on a heater, when the temp > 33, then I turn the heater
off. The ohter 2 sensors are outside and are used for the climate chnage experimnet.
