# vagrant-icub
Vagrant configurations files to create VirtualBox virtual machine with YARP and iCub-main sources and dependancies.

## Requirements

1. Virtualbox
2. Vagrant

## How to run:

1. clone this project
2. go in the desired virtual machine subdir (eg. ubuntu-xenial-64)
3. execute "vagrant up"
4. enjoy

## Default user credentials

The credentials (username and password) are the default for each vagrant box, see details below.

### Ubuntu based boxes

- username : ubuntu
- password :

The ubuntu user is configured as sudoer without password.

### Debian based boxes

Please use the default vagrant user, see [Vagrant documentation](https://www.vagrantup.com/docs/boxes/base.html)
