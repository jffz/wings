Wings
=========

A simple playbook that install Wings (Pterodactyl.io's daemon)

Requirements
------------

EL7 or Ubuntu 14.04 VPS or dedicated server

Role Variables
--------------

There is no variable at the moment as the playbook follow the official installations instructions.

Dependencies
------------

No dependencies.

Example Playbook
----------------
    - hosts: servers
      roles:
         - { role: jffz.wings }

License
-------

MIT

Author Information
------------------

jeff@hsfactory.net
