sbog/taskd
==========

Role to install and configure taskd server

#### Requirements

Ansible>=2.8

#### Role Variables

For full list of variables look to `defaults/main.yml` file.

#### Dependencies

None

#### Example Playbook

```yaml
- name: Install taskd
  hosts: taskd_servers
  roles:
    - taskd
```

#### License

Apache 2.0

#### Author Information

Stan Bogatkin (https://sbog.ru)
