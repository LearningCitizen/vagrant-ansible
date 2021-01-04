# Architecture
2 nodes setup: 2 nodes setup: 2 machines in Vagrant
Vagrant box: Os Centos 7 box

# Requirements

1. Supported Host OS:
  - Linux
  - MacOS
  - Windows
2. Vagrant >= 2.1.5
3. VirtualBox >= 5.2.18
4. Supported Guest OS: centos/7 box

# How to Start Lab

```bash
vagrant up
```

# How to run ansible provisioning from control-node

```bash
vagrant ssh control-node -c  "ansible-playbook /vagrant/provisioning/ansible/playbook.yml"
```
