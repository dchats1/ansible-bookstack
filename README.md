Role Name
=========

Deploys Bookstack and MariaDB using Podman.
https://www.bookstackapp.com/
https://github.com/linuxserver/docker-bookstack

Requirements
------------

Any host running podman.

Role Variables
--------------

bookstack_db: bookstack
bookstack_domain: example.com
bookstack_hostname: bookstack
bookstack_mariadb_pw: my_secure_password
bookstack_mariadb_root_pw: root_secure_password
bookstack_mariadb_user: bookstack
bookstack_podman_ip: 10.88.0.50
bookstack_podman_network: podman
bookstack_tz: America/New_York

Dependencies
------------

No dependencies at this time.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: bookstack
      roles:
         - ansible-bookstack

License
-------

BSD

Author Information
------------------

David Chatterton