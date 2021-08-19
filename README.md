# vagrant-ansible

Thanks to Vagrant we can provide 2 virtual machines in which we can use ansible.  
The machine virtualization provider used is Virtualbox.

Boxes used :  
* Centos

## Requirements 
- [Vagrant](https://www.vagrantup.com/downloads)
- [Virtualbox](https://www.virtualbox.org/wiki/Downloads)

## Useful commands

* Init a directory with vagrantfile
```bash
vagrant init centos/7
```
* Launch the virtual machine
```bash
vagrant up
```

* Connect by ssh to the virtual machine
```bash
vagrant ssh
```
