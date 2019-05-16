# air-quality
Arduino air quality monitoring

The purpose of this project is to develop an air quality monitoring system with an Arduino Uno microcontroller.

The sensor being used initially is a Plantower PMS5003 PM2.5 air quality sensor.  This sensor measures dust concentractions.  

The PM2.5 refers to particles that are 2.5 microns or smaller in diameter.  This sensor uses laser scattering to radiate suspended particles in teh air, then collects scattering light to obtain the curve of scattering light change with time.  The microprocessor calculates equivalent particle diameter and the number of particles with different diameter per unit volume. (Source: adafruit.com)

In future versions of the project a CO2 sensor will be added to measure carbon dioxide.

Initially measurements will be returned to the terminal using a serial connection to the Arduino via USB.  Eventually this will be replaced with some type of visualisation tool or device.
