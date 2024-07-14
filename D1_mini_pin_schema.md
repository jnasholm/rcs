# D1 mini pin schema

The room climate sensor IO pins are assigned according to the table below[^1][^2].

|Function|Pin|Comment|
|------------------------------|:--:|--------|
|Room climate sensors (i2c sda)|4|
|Room climate sensors (i2c scl)|5|
|System status LED onboard|2|
|Room climate sensor status LED|14|
|Room temperature sensor (DS18B20)|12|
|Room temperature sensor (NTC)|A0|Downstream configuration with 15kOhm resistance at 25°C
|Room temperature sensor power (NTC)|13|Supply +3.3V over a 10kOhm resistor

[^1]: [LOLIN D1 mini](https://www.wemos.cc/en/latest/d1/d1_mini.html)
[^2]: [ESP8266 Pinout Reference: Which GPIO pins should you use?](https://randomnerdtutorials.com/esp8266-pinout-reference-gpios/)
