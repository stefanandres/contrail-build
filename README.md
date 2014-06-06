# _contrails-build_

This code ought to compile opencontrails in vagrant to be used to integrate the binaries in a production OpenStack setup.
Currently it only supports Centos-6.5.

## Requirements

You need to have a personal github ssh key in your command line environment. vagrant will ssh-agent this key to the install script.
If you want to run it in the background, you need to configure your ssh key in the install_script.

## Installation/Running

1. install vagrant with VirtualBox support
2. `git clone https://github.com/stefanandres/contrails-build.git`
3. `cd contrails-build/centos65`
6. `vagrant up`
7. binaries currently are deployed in the VM in /tmp/contrails_install (vagrant ssh to enter VM)
