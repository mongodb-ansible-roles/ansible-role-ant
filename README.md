Ansible role for ant
==================================

Installs Ant

[![GitHub Actions](https://github.com/mongodb-ansible-roles/ansible-role-ant/workflows/Molecule%20Test/badge.svg)](https://github.com/mongodb-ansible-roles/ant/actions?query=workflow%3A%22Molecule+Test%22)
[![GitHub Actions](https://github.com/mongodb-ansible-roles/ansible-role-ant/workflows/Release/badge.svg)](https://github.com/mongodb-ansible-roles/ant/actions?query=workflow%3A%22Release%22)

Requirements
------------

None

Role Variables
--------------

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-------:|:--------:|
| `ant_url` | URL to download ANT from | string | "https://s3.amazonaws.com/boxes.10gen.com/build/apache-ant-{{ ant_version }}-bin.zip" | false |
| `ant_user` | User who will be running ANT | string | "" | false |
| `ant_version` | Version of ANT to download | string | "1.10.1" | false |

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
