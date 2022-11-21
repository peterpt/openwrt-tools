# openwrt-tools
Scripts for openwrt

## Scripts
change - This script changes your mac address from your wan port
- Some isps give a new ip address when mac adress of wan interface is different 
- the default wan interface name is "wan" in openwrt , if yours is different then
- edit the script and change line 7 with (wandev=your wan interface name)
- this script auto installs the required tools , make sure you are connected to internet
- when you run it .
- This script uses macchanger and dig to get a new ip .

## To install :
- connect to your router via ssh 
- cd /usr/sbin && wget https://github.com/peterpt/openwrt-tools/raw/main/change && chmod +x /usr/sbin/change

- to change your wan ip log in into your router using ssh and write change in the terminal
