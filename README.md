# Must2MQTT MQTT to modbus converter for MUST Inverter (forked fom https://github.com/softwarecrash/Solar2MQTT )

# Features:
- captive portal for wifi and MQTT config
- config in webinterface 
- get essential data over webinterface, get [all data](https://github.com/softwarecrash/Solar2MQTT/wiki/Datapoints-and-units) over MQTT
- classic MQTT datapoints or Json string over MQTT
- get Json over web at /livejson?
- firmware update over webinterface
- debug log on Wemos USB or Webserial
- [blink codes](https://github.com/softwarecrash/Solar2MQTT/wiki/Blink-Codes) for the current state of the ESP
- [Reset functions](https://github.com/softwarecrash/Solar2MQTT/wiki/Reset)
- [Support Home Assistant](https://github.com/softwarecrash/Solar2MQTT/wiki/HomeAssistant-integration)


**works with**
- MUST PV18 devices


**Main screen:**

![image](https://github.com/softwarecrash/Solar2MQTT/assets/17761850/de945ad5-29ad-476e-9562-a0eba1b4f2ce)

**Settings:**

![image](https://github.com/softwarecrash/Solar2MQTT/assets/17761850/075d1e66-3912-4a33-b7d3-a52da99c8553)

**Config:**

![image](https://github.com/softwarecrash/Solar2MQTT/assets/17761850/823093bf-8abe-4b7e-913f-7bac9420d108)


# How to use:
- Download the [latest Firmware](https://github.com/softwarecrash/Solar2MQTT/releases/latest)
- flash the bin file to an ESP8266 (recommended Wemos D1 Mini) with [Tasmotizer](https://github.com/tasmota/tasmotizer/releases)
- connect the ESP like the [wiring diagram](https://github.com/softwarecrash/Solar2MQTT/wiki/Wiring-Diagram)
- search for the wifi ap "Must2MQTT-AP" and connect to it
- surf to 192.168.4.1 and set up your wifi and optional MQTT
- that's it :)

### How-To video by Jarnsen

<a href="http://www.youtube.com/watch?feature=player_embedded&v=7u8hPLdXeso" target="_blank">
 <img src="http://img.youtube.com/vi/7u8hPLdXeso/0.jpg" alt="Watch the video" />
</a>



**POWER:** USB power from inverter USB port.

# Parts required to build

Most of the parts can be bought as modules, it's usually cheaper that way.

- ESP8266 - Wemos D1 Mini or ESP8266-01
- MAX485 UART-RS48 module 
- old RJ45 cable or connector
#
[basic functinality was forked from https://github.com/softwarecrash/Solar2MQTT]

command set taken from https://github.com/taHC81/MUST-ESPhome/blob/ae6d43f92bf3b2dc8efb78ba023e0eab26e041f2/PH1800%20PV1800%20EP1800%20PV3500%20EP3500%20RS485%20Modbud%20RTU%20communication%20Protocol%201.4.15.xlsx

[![LICENSE](https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

