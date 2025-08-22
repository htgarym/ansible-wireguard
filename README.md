# ansible-wireguard
Ansible Playbook for installing WireGuard on a Amazon Linux 2023 VM and acting as a central server for multiple clients.

## Running
This playbook is meant to run from the node itself and will only install everything on that single machine.

```shell
ansible-playbook -i inventory.ini playbook.yml
```
