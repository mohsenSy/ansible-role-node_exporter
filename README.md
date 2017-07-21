node_exporter
=========

This role can be used to install node_exporter for prometheus, currently on Ubuntu 14.04 and 16.04 only more will be added soon.

Requirements
------------

This role does not include any special requirements.

Role Variables
--------------

This role uses two variables both of them have default values:
* **NODE_EXPORTER_VERSION**: The version of node_exporter to install, default is 0.14.0.
* **NODE_EXPORTER_BIND_PORT**: The port used to bind node_exporter to it, default is 9100

Dependencies
------------

This role does not depend on any other roles to work.

Example Playbook
----------------


    - hosts: servers
      roles:
         - mohsenSy.node_exporter

License
-------

BSD

Author Information
------------------

If you have any questions or suggestions please contact me on

[twitter](https://twitter.com/mouhsen_ibrahim)

[linkedin](https://linkedin.com/in/mohsen-ibrahim-670b13112/)

email mohsen47@hotmail.co.uk
