# raspberry headless setup for wifi and ssh
1. Add file name **ssh** in root of sdcard
2. Add file named **wpa_supplicant.conf** in root of the sdcard with the below content
```
country=SG
ctrl_interface=DIR=/var/run/wpa_supplicant GROUP=netdev
update_config=1

network={
     ssid="MY_SSID"
     psk="MY_PASSWORD"
}
```
Update ssid and psk as per your credentials
