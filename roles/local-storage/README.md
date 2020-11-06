local-storage
=========

A brief description of the role goes here.

Requirements
------------

Worker nodes should have one or more disks to create PVs. Update device paths in the template localvolume-osd.yaml.j2 based on the disks in your nodes

Example Playbook
----------------

- hosts: localhost
  tasks:
    - include_role:
        name: local-storage

License
-------

MIT

