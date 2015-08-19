kapa-secureserver
=========

Playbook for installing Secure Server for X-Road (Kansallinen Palveluväylä).

Requirements
------------

- Ubuntu 14.04 or later on target machine.
- The `python-passlib` package is required on the initiating machine.
- Inventory file should preferably use FQDN instead of IP as these are passed to
  a script that generates certificates per host.

Dependencies
------------

### Role dependencies

- https://git.forgeservicelab.fi/ansible-roles/kapa-secureserver/

License
-------

MIT

Author Information
------------------

Jukka Nousiainen

FORGE Service Lab
