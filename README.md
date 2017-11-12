# HomeAssistant

###Useful Commands:

**Get Logs:** `tail -F /home/homeassistant/.homeassistant/home-assistant.log`

**Restart HASS:** `sudo systemctl restart home-assistant.service`

**Upgrade HASS:** `cd ~/fabric-home-assistant && fab upgrade_homeassistant && sudo reboot`

**Get Mosquitto Status:** `sudo systemctl status mosquitto`

**Force Date update:** 
```bash
sudo service ntp stop 
sudo ntpd -gq  
sudo service ntp start
```


**To launch the OpenZWave Control Panel (OZWCP) web application:**

1. Make sure Home Assistant is not running! So stop that first
1. Login to Raspberry `Pi ssh pi@your_raspberry_pi_ip`
1. Change to the OZWCP directory `cd /srv/homeassistant/src/open-zwave-control-panel/`
1. Launch the control panel `sudo ./ozwcp -p 8888`
1. Open a web browser to `http://your_pi_ip:8888`
1. Specify your Z-Wave controller, for example `/dev/ttyACM0` and hit initialize

###Useful Links
[Online YAML Parser](https://yaml-online-parser.appspot.com/)

