# jtprogru.hosts

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprogru/ansible-role-hosts/CI?label=CI) ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprogru/ansible-role-hosts/Release?label=Release) ![GitHub](https://img.shields.io/github/license/jtprogru/ansible-role-hosts)

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

  roles:
    - jtprogru.hosts
```

## License

See [LICENSE](LICENSE.md)
