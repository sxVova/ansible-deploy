Sentry deploy role
=========

A brief description of the role goes here.

Requirements
------------

Installed docker and docker-compose.


Example Playbook
----------------

    - hosts: servers
      become: true
      gather_facts: no
      roles:
         - { role: sentry_deploy_role }

License
-------

BSD

Author Information
------------------

https://www.sxvova.opensource-ukraine.org/
