Role Name
=========

This role installs and configures the CyVerse EZ cli and other convenience functions on a system.

This role is to be used in conjunction with the CyVerse EZ playbook: https://github.com/cyverse/cyverse-ez.git

Requirements
------------

This will require ansible to be installed on the target system

Role Variables
--------------

* EZ_INSTALL_DIR, the prefix for any software to be installed on the target system. If not defined, defaults to /opt
* ez_local_log: the full path to the installation log on the target system. If not defined, defaults to /var/log/cyverse-ez.log

Dependencies
------------

* Ansible


License
-------

BSD

Author Information
------------------

Feel free to contact Edwin Skidmore (edwin@cyverse.org) if you want more information
