# pc-setup

Ansible playbook to setup a new computer

usage example:

```sh
export TB_HOSTNAME="THE_HOST_NAME_TO_CONFIGURED" 
ansible-playbook --ask-become-pass --connection local --inventory localhost, 000-playbook.yml
```

notes:

- In the main branch, this playbook works with latest fedora that I am using. Currently it is Fedora 34.
- If an older version is needed, it should be available in a different branch.
