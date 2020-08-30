# nexus-iptables

Version: 20200830
Author: Steve Magnuson, AG7GN

iptables rules for the Nexus DR-X image.

## Installation

- Open a Terminal and run these commands:

		cd ~
		rm -rf nexus-iptables/
		git clone https://github.com/AG7GN/nexus-iptables
  		sudo cp /etc/iptables/rules.v4 /etc/iptables/rules.v4.previous
  		sudo cp /etc/iptables/rules.v6 /etc/iptables/rules.v6.previous
		sudo cp nexus-iptables/rules.v? /etc/iptables/
		sudo iptables-restore < /etc/iptables/rules.v4
		sudo ip6tables-restore < /etc/iptables/rules.v6

