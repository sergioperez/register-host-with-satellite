Role Name
=========


Requirements
------------

Role Variables
--------------

- satellite\_url:

Url of the Red Hat Satellite Server. Example: "https://satellite.hooli.es"

- ca\_consumer\_pkg\_name (Optional, targets the latest available if it is not specified)

Dependencies
------------

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: install-ca-consumer, satellite_url: https://satellite.hooli.es }

License
-------

GPLv2

Author Information
------------------

Sergio Pérez Fernández
