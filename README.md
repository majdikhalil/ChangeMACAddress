# ChangeMACAddress


ifconfig | grep broadcast #Find the list of connected devices on the network
arp -a #List them 


ifconfig en0 | grep ether #find your current mac address


sudo ifconfig en0 ether xx:xx:xx:xx:xx:xx #set new mac address
