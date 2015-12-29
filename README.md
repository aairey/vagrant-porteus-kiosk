# vagrant-porteus-kiosk

This is a Vagrantfile to start a preconfigured Porteus Kiosk 3.6 client.

## Usage

### This Vagrantfile

You can use the Vagrantfile from this repo as follows.

```
git clone https://github.com/aairey/vagrant-porteus-kiosk.git
vagrant up --provider=virtualbox
vagrant ssh
```
The default root password is "test".

### Through Atlas

The box is also available through [Atlas](https://atlas.hashicorp.com/aairey/porteus-kiosk), you can start using it by running:

```
vagrant init aairey/porteus-kiosk; vagrant up --provider=virtualbox
vagrant ssh
```
The default root password is "test".

## Notes
Currently only VirtualBox is supported.

The Setup Wizard is already run with the defaults and following selections made:
* DHCP
* Firefox as browser
** No Location Bar
* No HTTP Proxy
* VNC Server running
* SSH enable, root password is "test"

This repository may not seem of much use now, but in the future I hope to make and track changes here.

