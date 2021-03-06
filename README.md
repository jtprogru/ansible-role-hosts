# jtprogru.hosts

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprogru/ansible-role-hosts/CI?label=CI)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprogru/ansible-role-hosts/Release?label=Release)
![GitHub](https://img.shields.io/github/license/jtprogru/ansible-role-hosts)
[![Ansible Role](https://img.shields.io/ansible/role/54364)](https://galaxy.ansible.com/jtprogru/hosts/)
[![GitHub tag](https://img.shields.io/github/tag/jtprogru/ansible-role-hosts.svg)](https://github.com/jtprogru/ansible-role-hosts/tags)

Simple role for manage `/etc/hosts` file.


## Role Variables


See [`defaults/main.yml`](defaults/main.yml).


## Example Playbook

Example playbook:
```yaml
---
- name: Manage hosts file
  hosts: all
  become: true

  vars:
    host_prefix: '10.110.0.0/24'

  roles:
    - jtprogru.hosts
```

## Author

Michael Savin aka `@jtprogru`

Twitter: [![Twitter Follow](https://img.shields.io/twitter/follow/jtprogru?color=gree&style=plastic)](https://twitter.com/jtprogru/)

## License

See [LICENSE](LICENSE.md)
