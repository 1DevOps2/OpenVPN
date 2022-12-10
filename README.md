
#### Replace ${MY_CONFIGURATION_FILE} with the OpenVPN configuration file you want to use. 

	openvpn2 --config ${MY_CONFIGURATION_FILE} --verb 6

Note: If this configuration includes the --daemon option, the VPN session will be started in the background and the user is given the command line back again. 

	openvpn2 --config ${MY_CONFIGURATION_FILE} --verb 6 --daemon

#### Example
	- openvpn2 --config anasVPN.ovpn --verb 6 
	- openvpn2 --config /home/ubuntu/MYteam.ovpn --verb 6
	- openvpn --config anasVPN.ovpn --verb 6 --ignore-unknown-option block-outside-dns
