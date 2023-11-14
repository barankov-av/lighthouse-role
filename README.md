Lighthouse
=========

This role pre-install nginx & git client, clone lighthouse code by git client, prepare nginx config and start nginx.

Role Variables
--------------

|vars|description|
|-------|-----------|
|lighthouse_nginx_port|This variable allows you to set the port|

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: lighthouse-role }

License
-------

MIT

Author Information
------------------

Barankov Anton.
