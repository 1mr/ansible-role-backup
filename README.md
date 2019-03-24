Backup
======

This role copy backup scripts.

Requirements
------------

This role requires ansible 1.4 or higher.

Role Variables
--------------

The variables that can be passed to this role and a brief description about them are as follows:

    backup:
      - name: etc
        script: backup_etc.sh

        

Dependencies
------------


Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: 1mr.backup, tags: backup }

License
-------

BSD


