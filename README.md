[![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-sgdb-postgresql.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-sgdb-postgresql)
---
# IaC: with[Ansible](https://www.ansible) role to install and configure [AWX](https://github.com/ansible/awx)
------------

Description
------------
 *

Requirements
------------

 *

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* None

Example Playbook
----------------
```yaml
---
- hosts: localhost
  vars:
    - name: value
  roles:
    - iac-ansible-postgresql
```

License
-------

[GPLv3](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
