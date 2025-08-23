## ESP8266 Deauther Modified for the Wemos D1 Mini Board (post-troubleshooting)
The original one is here: [Link](https://github.com/SpacehuhnTech/esp8266_deauther)

The SpaceHuhn one has some issues with screen setup and button setup, so I've modified the code and it somehow works now.
Issues fixed:
- screen not working
- buttons not working
- screen goes off, display=true setting not retained

Tested with Wemos D1 Mini and NodeMCU ESP8266, using only 0.96" I2C OLED.
*(NOTE: I changed the starting screen's PROGMEM text values to suit my custom project.)*
