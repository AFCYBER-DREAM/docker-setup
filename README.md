Docker Setup
=========

Installs and configures docker using docker-storage.

Requirements
------------

None

Role Variables
--------------

| Variable Name | Description | Default |
|---------------|-------------|---------|
| docker_device | The raw disk device to use for /var/lib/docker. | **/dev/sdb** |

Dependencies
------------

None

Example Playbook
----------------

A use example:

    - hosts: servers
      roles:
         - { role: docker-setup }

License
-------

MIT

Author Information
------------------

The Development Range Engineering, Architecture, and Modernization (DREAM) Team.
