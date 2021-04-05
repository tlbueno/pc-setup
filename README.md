# pc-setup

Ansible playbook to setup a new computer

usage example:

```sh
export TB_HOSTNAME="THE_HOST_NAME_TO_CONFIGURED" 
ansible-playbook --ask-become-pass --connection local --inventory localhost, 000-playbook.yml
```
