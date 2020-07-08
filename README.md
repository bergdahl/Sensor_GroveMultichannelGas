# Sensor_GroveMultichannelGas

Arduoino sketch for connecting a [SEEED Multichannel Gas Sensor V1](https://wiki.seeedstudio.com/Grove-Multichannel_Gas_Sensor/) to a MQTT server.

Use [my forked version of their library](https://github.com/bergdahl/Mutichannel_Gas_Sensor) of the library if you are using this sensor with a non AVR/SAMD board. It contains a fix for the compilation error you will get.

# Usage

Change the file named `settings.h` with your settings.

```
#define WIFI_SSID "<Your WiFi SSID>"
#define WIFI_PASSWORD "<Your WiFi Password"

#define MQTT_SERVER "<Your MQTT Server address>"
#define MQTT_USER "<Your MQTT Username>"
#define MQTT_PASSWORD "<Your MQTT Password>"
```
