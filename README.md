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

###Useful Links
[Online YAML Parser](https://yaml-online-parser.appspot.com/)

