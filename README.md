Docker
======

Installs docker, configures the docker group and permissions.

Usage
-----

To utilize this role, add it to the `requirements.yml` file inside the ansible folder:

    - src: git+https://github.com/magenta-aps/ansible-role-docker.git
      version: master
      name: docker

Requirements
------------

Must be run against debian stretch.

Example Playbook
----------------

    - hosts: all
      roles:
         - docker

License
-------

MPLv2

Author Information
------------------

skeen - Emil Madsen
