SSLScan
=========

Ansible Galaxy role for SSLScan

Requirements
------------

Role builds from source. Source repositories must be enabled in your sources.list.

Role Variables
--------------

sslscan_git_location: '/opt'

Dependencies
------------

leesoh.git

Example Playbook
----------------

- hosts: servers
  roles:
      - { role: leesoh.sslscan }

License
-------

BSD-3

Author Information
------------------

SSLScan: https://github.com/rbsec/sslscan
