# ansible-ansible
Ensure ansible is intstalled on linux servers

## Requirements
None

## Role Variables
- ansible_version: version of ansible you wanted to install.

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