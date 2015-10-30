Node
====

Install Node from NodeSource & any other user defined packages from apt-get for Debian/Ubuntu.

Requirements
------------

No known pre-requisites.

Role Variables
--------------

### version
Please see [NodeSource Node.js Binary Distributions](https://github.com/nodesource/distributions) for the versions you can install.  
**default value** `4.x`

### apt
List of packages to install


Dependencies
------------

No dependencies.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: bencooling.node, version: 4.x, apt: ['graphicsmagick'] }

License
-------

BSD

Author Information
------------------

Ansible role maintained by [Ben Cooling, Gold Coast Web Developer](bcooling.com.au)
