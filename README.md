Ansible Role User-Check 
=========

This playbook simply checks and prints local users on a remote host. 

Requirements
------------


Role Variables
--------------
 No specific variables are used here

Dependencies
------------
- Ansible 

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: tedleyem.local-user-check, x: 42 }

License
-------

BSD

Issues 
------------------
https://github.com/tedleyem/ansible-role-local-user-check/issues

