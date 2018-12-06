## Welcome to diyHue

This project emulates a Philips Hue Bridge that is able to control ZigBee lights (using Raspbee module, original Hue Bridge or IKEA Tradfri Gateway), Mi-Light bulbs (using MiLight Hub), Neopixel strips (WS2812B and SK6812) and any cheap ESP8266 based bulb by replacing the firmware with a custom one. It is written in python and will run on all small devices such as the RaspberryPi. Arduino sketches are provided for the Hue Dimmer Switch, Hue Tap Switch and Hue Motion Sensor. Lights are two-way synchronized so any change made from original Philips/Tradfri sensors and switches will also be applied to the bridge emulator.

<img src="/assets/images/hue-map.png" alt="diyHue ecosystem" width="100%" />

## DOWNLOAD:
  - [View/Download the Bridge Emulator on GitHub]({{ site.github.repository_url }})
  - [Create your own lights](https://github.com/diyhue/Lights)
  - [Create your own devices](https://github.com/diyhue/Devices)
  
## Working HUE futures:
  - Control lights (all functions)
  - Control groups (all functions)
  - Scenes (all functions)
  - Routines
  - Wake up
  - Go to sleep
  - Switches (custom esp8266 switches)
  - Autodiscover lights
  - Hue entertainment

## Working devices and applications:
  - Amazon Alexa (control only the lights)
  - Logitech Harmony
  - Tradfri Gateway
  - Hue Bridge (original + other emulators)
  - Home Assistant
  - Domoticz
  - Openhab
  - Philips Ambilight TV's 
  - Kodi Hue Ambilight
  - Jeedom
  - Hue Sync for PC
  
## Working smartphone applications:
  - Hue (official application)
  - [Hue Essentials](https://play.google.com/store/apps/details?id=com.superthomaslab.hueessentials) - recommended
  - hueManic
  - OnSwitch
  - HueSwitcher
  - LampShade

## Supported lights:
  - WS2812B and SK6812 smart led strips
  - MiLight
  - Yeelight
  - LYT8266
  - Phillips Hue
  - Ikea Tradfri
  - Pwm RGB-CCT
  - Pwm RGBW
  - Pwm RGB
  - Pwm CCT
  - Pwm Dimming (up to 6 lights for every esp8266)
  - On/Off plugs/lights (up to 6 lights for every esp8266)
  - On/Off 433Mhz devices (multiple devices for every esp8266)

## Not working:
  - Remote API (Will likely never work)
  - Home & Away future from Hue app (require remote api)
  - Google Home (require remote api)
  - Eneco Toon (very likely it use cloud service detection)

### Support or Contact

Having trouble with diyHue? Check out our [documentation](https://github.com/diyhue/diyHue/wiki) or [join us on slack](https://slackinvite.squishedmooo.com/) and we’ll help you sort it out.
