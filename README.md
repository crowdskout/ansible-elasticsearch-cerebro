Role Name
=========

Installs cerebro tool for managing elasticsearch clusters.

Requirements
------------

systemd


Role Variables
--------------

    elastic_cerebro_version: <default: 0.6.5>
    elastic_cerebro_port: <default: 9000>
    elastic_cerebro_listen_host: <default: 0.0.0.0>


Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - role: crowdskout.elasticsearch-cerebro
          elastic_cerebro_version: 0.5.0
          elastic_cerebro_port: 9201

License
-------

BSD
