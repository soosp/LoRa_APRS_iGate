# Richonguzman / CD2RXU LoRa APRS iGate
# Firmware for Tx and Rx !!!

LoRa APRS iGATE for:
- LILYGO ESP32 LoRa v2-1-1.6
- ESP32 Wroom Dev +  SX1278 LoRa Module for a DIY Version

__________________________________________

Achievements:
- listening to LoRa packets the same as messages for Stations/Callsing in near 80Kms.
- transmiting messages listened from APRS-IS to LoRa

__________________________________________

Instrucctions (add your information into the '/data/igate_conf.json'):

1.- Change "callsign" from "NOCALL-10" to your CALLSIGN + SSID

2.- Change "SSID" from "WiFi_AP_1"  to your WIFI-NAME

3.- Change "Password" from "password_WiFi_2" to your WIFI-PASSWORD

4.- Add the GPS to "Latitude" and "Longitude"  (info from GoogleMaps) of new LoRa iGate

5.- Change "passcode" from "XYZVW" to yours (remember that is 5 digits integer)


__________________________________________
Versions:
2023.02.10 - First Beta (receiving LoRa Beacon/Packets and uploading to APRS-IS).
2023.02.17 - Receiving Feed from APRS-IS.
2023.03.01 - Tx Packet from APRS-IS to nearby LoRa Stations.
2023.05.12 - Tx Packet from APRS-IS format Correction.
2023.05.19 - Saving Last-Heard Stations for validating Tx Responses
__________________________________________


Enjoy!!!

# Hope You Enjoy this, 73 !!  CD2RXU , Valparaiso, Chile

