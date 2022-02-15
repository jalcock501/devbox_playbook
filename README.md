# Devbox Playbook

Ansible playbook to roll my devboxes in a one-shot

Supported OS: Debian 10

## Usage


Set IP address in:
```
inventory/dev/hosts.yml
   ansible_host 
   ipv6
```
Run playbook:
```
$ ansible-galaxy install -r roles/requirements.yml --force
$ ansible-playbook -i inventory/dev/hosts.yml site.yml
```


## License
---
MIT


## Author Information
---
This role was created in 2022 by Jim Alcock