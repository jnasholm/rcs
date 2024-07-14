# rcs
<!-- [![GitHub release (latest by date)](https://img.shields.io/github/v/release/jnasholm/rcs)](https://github.com/jnasholm/rcs/releases) -->
<!-- ![GitHub last commit](https://img.shields.io/github/last-commit/jnasholm/rcs) -->

# ESP Room Climate Sensor

Project to create a smart room climate sensor for private homes with a hydronic underfloor heating system, a radiator heating system, or a combination of both. Brief project description:

- The room climate sensor is a [D1 mini](https://www.wemos.cc/en/latest/d1/d1_mini.html) programmed with [ESPHome](https://esphome.io/).
- Room climate data is provided either by the Bosch [BMP280](https://www.bosch-sensortec.com/products/environmental-sensors/pressure-sensors/bmp280/) temperature and pressure sensor, or the Bosch [BME280](https://www.bosch-sensortec.com/products/environmental-sensors/humidity-sensors-bme280/) temperature, humidity and pressure sensor.
- Floor temperature sensor is either an analog [NTC](https://en.wikipedia.org/wiki/Thermistor) or a digital [DS18B20](https://www.energibutiken.se/sv/dallas-1-wire-givare/161-dallas-1-wire-pro-kapslad-givare-6-mm-10-meter-02004.html). Linear analog sensors [RTD/PT100/PT1000](https://www.omega.com/en-us/temperature-measurement/temperature-wire-sensors/hsrtd/p/HSRTD-3-100-A-10M) will also be added in he future.
- Supply voltage for the room climate sensor is +12VDC.

## Description
The room climate sensor is designed to be a replacement for legacy wired room thermostats. 
