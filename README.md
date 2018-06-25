# ChangeMACAddress

#Find the list of connected devices on the network
ifconfig | grep broadcast
arp -a

#find your mac address 
ifconfig en0 | grep ether

#set new mac address
sudo ifconfig en0 ether xx:xx:xx:xx:xx:xx
