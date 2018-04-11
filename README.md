Safe Restart Apache2 Handler
=========

Ansible role with a handler that restarts apache only if the configcheck passes

Requirements
------------
apache 2.x with `apachectl configtest`

Role Variables
--------------


Dependencies
------------
None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      tasks:
         - debug: msg="run the handler"
           changed_when: yes
           notify: safe restart apache

License
-------

Apache

Author Information
------------------

https://github.com/jxn
