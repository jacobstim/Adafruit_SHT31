# Adafruit_SHT31D
SHT31-D driver using the Adafruit Unified Sensor Driver framework

This library is a wrapper arounds [Adafruit's original SHT31 sensor library](https://github.com/adafruit/Adafruit_SHT31) to make it compatible with Adafruit's own and extremely useful [Unified Sensor Driver framework](https://github.com/adafruit/Adafruit_Sensor). The wrapper itself was inspired heavily by the [DHT_Unified](https://github.com/adafruit/DHT-sensor-library/) wrapper they provide for the DHT sensors.

Furthermore, this library implements periodic mode for measurements and sensor-triggered alerts supported by the SHT31-D but never implemented by Adafruit. The examples explain how to use these additional functionalities.
