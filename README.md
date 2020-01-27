Ansible role for ant
==================================

Installs Ant

[![GitHub Actions](https://github.com/mongodb-ansible-roles/ant/workflows/Molecule%20Test/badge.svg)](https://github.com/mongodb-ansible-roles/ant/actions?query=workflow%3A%22Molecule+Test%22)
[![GitHub Actions](https://github.com/mongodb-ansible-roles/ant/workflows/Release/badge.svg)](https://github.com/mongodb-ansible-roles/ant/actions?query=workflow%3A%22Molecule+Test%22)

Requirements
------------

None

Role Variables
--------------

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-------:|:--------:|
| name | desc | type | default | required |

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: ansible-role-ant
```

License
-------

[Apache License](LICENSE)
