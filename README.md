# ESP8266 forced light-sleep test

Target solution is forcing ESP8266 into indefinite light-sleep with predefined wake-up button which sends an MQTT message immediately on press. Forced light sleep, however, seems only to work while fully disconnecting the wifi connection during the process, causing several seconds long delay on wake-up trying to reconnect the wifi. I am still trying to find a way to use light-sleep while maintaining the router connection. 


Hardware: 1) ESP8266-01, 2) Wemos D1 mini
Software: Arduino IDE 1.8.13
