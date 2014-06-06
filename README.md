# _contrails-build_

This code ought to compile opencontrails in vagrant to be used to integrate the binaries in a production OpenStack setup.
Currently it only supports Centos-6.5.

## Installation/Running

1. install vagrant with VirtualBox support
2. git clone https://github.com/stefanandres/contrails-build.git
3. cd contrails-build/centos65
4. manually add your personal github key in the install_contrails Script
5. adjust the cpu/memory count if needed in the Vagrantfile
6. vagrant up
7. binaries currently are deployed in the VM in /tmp/contrails_install
