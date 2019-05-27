Role Name
=========


Requirements
------------

Role Variables
--------------

- sat\_activation\_keys:

AKs separated by comma to register the host with Red Hat Satellite

- sat\_organization\_id

Org ID to register the host at

Dependencies
------------

Example Playbook
----------------

    - hosts: servers
      vars:
        sat_activation_keys: "rhel7,jboss"
        sat_org_id: "PiedPiper"
      roles:
         - { role: register-with-satellite }

License
-------

GPLv2

Author Information
------------------

Sergio Pérez Fernández
