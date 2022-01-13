Role Name: IC-webapp
=========

Deploy a odoo 

Requirements
------------
docker host on target machine
pip docker-py and docker_network modules

Role Variables
--------------

just go take a look in defaults

Dependencies
------------

ansible-galaxy install unklebens.odoo_role

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
- name: Wordpress in docker deployement
  hosts: centos:ubuntu
  become: true
  vars_files:
    - secret.yaml
  roles:
    - unklebens.docker_role
    - unklebens.ic_webapp_role
```

License
-------

open source take it sell it idc

Author Information
------------------

Fahim
Honorable mentions:
 -  SADO Frazer
 -  The marble machine builder (you know who you are)
