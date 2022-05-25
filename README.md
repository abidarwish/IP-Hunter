# IP Hunter for ASUS Router

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

Hunt public IP 113.211

requirement : Huawei Modem with AIO installed

Follow these steps:

1. Login to ASUS webui at 192.168.50.1 or 192.168.1.1
2. Go to Administration > System > allow ssh, set port and press Apply
3. Open terminal like Putty on PC or Shelly on ios/android
4. Login to router's console and copy/paste this command :

```
rm -rf iphunter && wget -q https://raw.githubusercontent.com/abidarwish/IP-Hunter/main/iphunter && bash iphunter
```

5. Follow instructions on the screen and wait until your modem connects to the intended public IP
