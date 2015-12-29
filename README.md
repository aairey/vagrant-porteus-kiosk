# vagrant-porteus-kiosk

This is a Vagrantfile to start a preconfigured Porteus Kiosk 3.6 client.

## Usage

The box is available through [Atlas](https://atlas.hashicorp.com/aairey/porteus-kiosk), you can start using it by running:

'''
vagrant init aairey/porteus-kiosk; vagrant up --provider=virtualbox
'''
Currently only VirtualBox is supported.

## Notes
The Setup Wizard is already run with the defaults and following selections made:
* DHCP
* Firefox as browser
** No Location Bar
* No HTTP Proxy

This repository may not seem of much use now, but in the future I hope to make and track changes here.
