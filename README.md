Role Name
=========

Installs cerebro tool for managing elasticsearch clusters. 

Requirements
------------



Role Variables
--------------


elastic_cerebro_version: <version of released tool>
elastic_cerebro_port: <port, defaults to 9000>
elastic_cerebro_listen_host: <ip to listen on, defaults to 0.0.0.0>



Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: crowdskout.elasticsearch-cerebro, cerebro: 0.5.0, elastic_cerebro_port: 9201 }

License
-------

BSD

