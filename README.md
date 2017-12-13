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

None

Example Playbook
----------------

Get going with:

    - hosts: servers
      roles:
         - { role: leesoh.sslscan }

License
-------

BSD

Author Information
------------------
SSLScan: https://github.com/rbsec/sslscan
