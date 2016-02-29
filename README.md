mamercad.minecraft
==================

Stands up a Minecraft server on RHEL/CentOS

Warnings
--------

The role puts SELinux into permissive mode and disables firewalld

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

    - hosts:
        - minecraft
      roles:
        - mamercad.minecraft

License
-------

GPLv3

Author Information
------------------

Mark Mercado <mamercad@umflint.edu>

