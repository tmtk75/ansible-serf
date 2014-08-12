consul
=========
Ansible role for [serf](http://www.serfdom.io/).
This role ensures that serf runs as a daemon.

Requirements
------------
- unzip command on remote hosts

Role Variables
--------------
- version
- sha256sum

Dependencies
------------
No dependencies.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: tmtk75.serf }

License
-------
MIT

Author Information
------------------
github: http://github.com/tmtk75

twitter: https://twitter.com/tmtk75

blog: http://blog.tmtk.net

