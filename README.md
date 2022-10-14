# Automated Workstation Setup
Automated workstation setup using Ansible

## Setup
```bash
apt install python3.10
python3 -m pip install ansible
```

## Usage
```bash
ansible-playbook wks-setup.yml --ask-become-pass
```

## Post Run
1. Open terminal and complete powerlevel10k setup