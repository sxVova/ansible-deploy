Flask role 
=========

This role allows you to raise a container with a flask application.

Requirements
------------

Installed docker and docker-compose

Role Variables
--------------

docker-compose.yml.j2 - file for loading the necessary version of the container and port forwarding

Example Playbook
----------------

    - hosts: flask
      become: true
      gather_facts: no
      roles:
         - { role: flask_role }

License
-------

BSD

Author Information
------------------

https://www.sxvova.opensource-ukraine.org/
