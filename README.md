# ansible-playground
This repository contains:
* Ansible quickstart for local playground
* Playbook for provisioning Docker Swarm
* CI pipeline for Azure Devops

### Dependencies
An Ansible 2.7 or higher installation. Vagrant 2.2.0 or higner installation. Ansible role `atosatto.docker-swarm`

### How to:
Customize *inventory* file with your target hosts, then just `ansible-playbook localPlaybook.yaml -i inventory`

### Useful References
  * Ansible User Guide: https://docs.ansible.com/ansible/latest/user_guide/index.html
  * Best Practice and Tips: https://max.engineer/six-ansible-practices
  * Local WSL Playground: https://binary.run/guide/vagrant-ansible-and-virtualbox-on-wsl-windows-subsystem-for-linux/
  * Ansible Role for docker setup: https://github.com/atosatto/ansible-dockerswarm
