ansible-role-mlocate
====================

ansible role to install and update it's database if no database
exists.

Requirements
------------

* Ansible 2.2
* EL7

Role Variables
--------------

no variables.

Dependencies
------------

no dependencies.

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: kumarstack55.ansible_role_mlocate
           vars:
             keymap_vc_keymap: jp

License
-------

MIT

Author Information
------------------

kumarstack55@gmail.com
