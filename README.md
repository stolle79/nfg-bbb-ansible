# nfg-bbb-ansible
Ansible for NfG / BBB

This Repository has submodules. To clone it you have to

$ git submodule init

to initialize your local configuration file, and

$ git submodule update

to fetch all the data from that project and check out the appropriate commit listed in your superproject.

# Installing Ansible on Ubuntu
$ sudo apt update
$ sudo apt install software-properties-common
$ sudo apt-add-repository --yes --update ppa:ansible/ansible
$ sudo apt install ansible