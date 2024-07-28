Role Name
=========

This Ansible role installs apache2 and deploys a simple fitness tracker web application

Requirements
------------

The role is designed for Ubuntu systems

Role Variables
--------------

No variables required for this role

Dependencies
------------

No dependencies

Example Playbook
----------------

    - hosts: servers
      become: true
      roles:
         - { role: username.rolename, x: 42 }

