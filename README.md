# Setup
- #homeassistant is required and #esphome
- you need working wifi signal next to your gas meter 
- gasmeter, i have an G4 RF1 
- some sort of ESP8266, i am using a Wemos D1 mini
- hall sensor and breakout board, i used a KY-024  (pay attention to the voltage, it needs to output 3,3v not 5v)

# Detailed Video in German: 
https://youtu.be/yp7ZDe6VlVM

Example Code i used to create a smart gasmeter for a typical german Gas Meter
check out 00-gasmeter.yaml

# Install
- create a new board / instance in ESPhome in your Homeassistant
- add the code from 00-gasmeter.yaml
- change the api and secret keys of the yaml file 
- check the analog input voltages and adjust them in the yaml file

- it can take quite some testing until you figured out the right values for the upper and lower limit

# Hardware:

IMPORTANT! If you want to use variant 2, you need to have an 49E hall Sensor. 49E will give an output based on the magnetic field, not only if there is a field or not. 
Some boards are labeled as 49E but have other Hall sensors. 
Variante 1: 
Hall Sensor https://amzn.to/3H5S6zG *

Variante 2:
49E lineare Hall Sensoren: https://amzn.to/4100lq5 * 

ESP8266 https://amzn.to/3kBZawl * 
Netzteil https://amzn.to/3XDVOaI *

Sämtliche mit „*“ markierten Links hängen mit Amazon Partnerprogrammen zusammen. Sie dienen dir als potentiellen Käufer als Orientierung und verweisen explizit auf bestimmte Produkte. Sofern diese Links genutzt werden, kann im Falle einer Kaufentscheidung eine Provision an mich ausgeschüttet werden. Bei einem Kauf über diese Links fallen natürlich keine Mehrkosten an. Danke!!

All links marked with "*" are related to Amazon affiliate programs. They serve you as a potential buyer as an orientation and refer explicitly to certain products. If these links are used, a commission can be paid to me in case of a purchase decision. In case of a purchase via these links, there are of course no additional costs. Thank you!!


