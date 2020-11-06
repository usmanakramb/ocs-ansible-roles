ocs-local-vol
=========

Deploy OCS using local storage

Requirements
------------

3 Worker nodes
Disks to be used for local storage should be attached to the worker nodes


Role Variables
--------------

Default storage class is set to RBD:
default_storageclass: "ocs-storagecluster-ceph-rbd"

Dependencies
------------

Local storage operator has already been deployed (local storage role can be used)

Example Playbook
----------------

- hosts: localhost
  tasks:
    - include_role:
        name: ocs-local-vol

License
-------

MIT
