# RaspberryPi_Based projects
These are the Raspian image files for the Raspberry Pi based open source Bacnet controller
Installation Guid followed
https://pimylifeup.com/raspberry-pi-wireguard/


wg0.conf is the config file of wireguard server 


ClientConfig.conf is the wireguard config file. 
add tunnel ClientConfig.conf file and press activate.
now ping the IP of PI in commond prompt

have to be replaced with wg0.conf at the /etc/wireguard/

To turn on VPN 
wg-quick up wg0

To turn off VPN 
wg-quick down wg0




