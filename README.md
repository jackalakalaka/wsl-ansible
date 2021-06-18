# Ansible: Ubuntu WSL

## Description
Ansible Project for configuring and maintaining an Ubuntu WSL installation on Windows.

## Requirements
Set up Ansible and Git
```bash
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install -y ansible git
```

## Usage
```bash
ansible-playbook -i inventory.yml -K wsl.yml
```
