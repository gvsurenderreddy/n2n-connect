n2n-connect
===========

n2n-connect is a simple wrapper script around N2N's edge program that allows you to easily manage and connect to N2N networks.

Installation
------------

Copy the n2n-connect script to a directory inside your $PATH. E.g.

	sudo cp n2n-connect /usr/local/bin

Next create the profile directory:

	sudo mkdir /etc/n2n-connect
	sudo chmod 700 /etc/n2n-connect
	sudo cp example /etc/n2n-connect

Configuration
-------------

Take a look into the file `/etc/n2n-connect/example` and adjust the configuration options. Save as a new file inside the profile directory. E.g. `/etc/n2n-connect/mynet`

Usage
-----

n2n-connect requires only a single command line argument: the name of the profile. Following the example above you would connect to your newly created network profile by typing:

	n2n-connect mynet
