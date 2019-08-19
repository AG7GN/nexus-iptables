# hampi-iptables
 
iptables rules for the hampi image.

## Installation

- Open a Terminal and run these commands:

		cd ~
		rm -rf hampi-iptables/
		git clone https://github.com/AG7GN/hampi-iptables
		cd hampi-iptables
		sudo cp rules.v? /etc/iptables/
		sudo iptables-restore < /etc/iptables/rules.v4
		sudo ip6tables-restore < /etc/iptables/rules.v6

