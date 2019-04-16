# ansible-ansible
Ensure ansible is intstalled on linux servers

## Requirements
This role needs Pip to be installed first, please ensure pip is installed before using this role, you can use (ansible-pip)[https://github.com/traveloka/ansible-pip]

## Role Variables
- ansible_pip_version: version of ansible you wanted to install.

## Example Playbook
```yaml
---
- hosts: servers
  vars:
   ansible_version:  "2.6.0"
  roles:
    role: ansible-ansible
```

## License
MIT 