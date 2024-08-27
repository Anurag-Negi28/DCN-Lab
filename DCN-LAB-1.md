# Modes in packet tracer-

- User Mode
- Privileged Mode
- Global Configuration mode
- Interface Mode

# Commands in packet tracer

config terminal  =We are in local configuration mode

hostname switch10007 =Name of the switch

enable secret lab1 =set the password(for configuration mode)

line con 0 =to set the line configuration mode

password cisco=to set password in the interface mode

exit =to exit the line interface

line vty 0 4 =to set the virtual terminal for 5 remote access terminals

password cisco =to set the password

login

service password-encryption =to encrypt the password

do show run =to see the configuration in other modes

banner motd $ Message $ =to print the message of the day

# Set the IP address

interface vlan1 =we cannot assign Ip to a switch we assign it to vlan

ip address  192.168.1.1 255.255.255.0 =set the IP address

no shut =turn on the switch

exit =to exit the mode
