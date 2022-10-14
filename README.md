# Setup
- #homeassistant is required and #esphome
- you need working wifi signal next to your gas meter 
- gasmeter, i have an G4 RF1 
- some sort of ESP8266, i am using a Wemos D1 mini
- hall sensor and breakout board, i used a KY-024  (pay attention to the voltage, it needs to output 3,3v not 5v)

Example Code i used to create a smart gasmeter for a typical german Gas Meter
check out 00-gasmeter.yaml

# Install
- create a new board / instance in ESPhome in your Homeassistant
- add the code from 00-gasmeter.yaml
- change the api and secret keys of the yaml file 
- check the analog input voltages and adjust them in the yaml file
- it can take quite some testing until you figured out the right values for the upper and lower limit

