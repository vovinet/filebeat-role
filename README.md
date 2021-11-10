Filebeat Deployment Role
=========

This role deploys Filebeat into debian-based or RHEL-based Linux OSes.

Requirements
------------

OS Supported:
* CentOS
* Red Hat Enterprise Linux
* Ubuntu
* Debian

Role Variables
--------------

| Variable name | Default | Description |
| filebeat_version | 7.14.0 | Filebeat version to be installed |
| filebeat_install_type | remote | Installation type. "remote" flag will force fetching distro from elastic.co |

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: filebeat.role }

License
-------

MIT

Author Information
------------------

Please visit my site: https://zubarev.su/ ( joke =)
