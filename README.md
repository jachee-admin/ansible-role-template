# ansible-role-template

Skeleton for an idempotent Ansible role + sample playbook.

## Quickstart
```bash
ansible-galaxy init roles/common
# This repo already contains a ready-made role structure.
ansible-playbook -i inventory.ini playbooks/site.yml --check
```
