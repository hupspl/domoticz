# Domoticz
Raspberry PI Domoticz install

Instalacja konsola Raspberry PI <br>

# Aktualizacja systemu

`sudo apt-get update && sudo apt-get -y upgrade && sudo apt-get -y autoremove`

# Instalacja Domoticz

` sudo curl -sSL install.domoticz.com | sudo bash`

# DOMOTICZ SERVER

`sudo /etc/init.d/domoticz.sh start`

`sudo /etc/init.d/domoticz.sh stop`

`sudo /etc/init.d/domoticz.sh restart`

`sudo /etc/init.d/domoticz.sh status`

# Domoticz MQTT konfiguracja

1. Instalacja MQTT: 

`sudo apt-get install mosquitto mosquitto-clients`

2. Zrobić użytkownika mqtt:

`sudo mosquitto_passwd -c /etc/mosquitto/pwfile mqtt`

3. Dodaj kilka reguł do konfiguracji: 
 
 `sudo vim /etc/mosquitto/mosquitto.conf`

