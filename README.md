ansible_role_certbot_auto
=========

A role to install [EFF's Certbot](https://certbot.eff.org/) tool using their `certbot-auto` wrapper. 

Requirements
------------

The role itself should handle any requirements needed.

Role Variables
--------------

### vars/main.yml

`google_dns_plugin: yes`

By default, install the Google DNS plugin for wild card SSL certificates using Google Cloud DNS.

Dependencies
------------

None that I am aware of.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: dpendolino.ansible_role_certbot_auto }

License
-------

GNU General Public License v3.0

Author Information
------------------

Daniel Pendolino

[https://github.com/dpendolino](https://github.com/dpendolino)
