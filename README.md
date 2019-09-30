[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-SGBD%20PostgreSQL-blue.svg)](https://galaxy.ansible.com/wluisaraujo/postgresql) [![Build Status](https://travis-ci.org/wluisaraujo/ansible-role-postgresql.svg?branch=master)](https://travis-ci.org/wluisaraujo/ansible-role-postgresql)
---
# IaC: with [Ansible](https://www.ansible) role to install and configure [PostgreSQL](https://www.postgresql.org/)
------------

Description
------------

 *

Requirements
------------

 *

Installation
------------

```console
vagrant@localhost:~$ ansible-galaxy install wluisaraujo.postgresql
vagrant@localhost:~$ ansible-galaxy install -r wluisaraujo.postgresql/requirements.txt
```

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
    - postgresql
...
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
