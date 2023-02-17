![Ansible Lint](https://github.com/johanneskastl/ansible-role-samba4_ad_domaincontroller/workflows/Ansible%20Lint/badge.svg)

samba4_ad_domaincontroller
=========

Prepare a Samba4 ActiveDirectory domaincontroller (install packages, ...).

Requirements
------------

None.

Role Variables
--------------

TBD.

Please pay attention, this role previously used a variable `use_bind9_for_DNS`, that was renamed to `use_bind9_for_dns`. Please adjust your playbooks accordingly.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: 'johanneskastl.samba4_ad_domaincontroller'

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
