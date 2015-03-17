kapa-secureserver
=========

Playbook for installing Secure Server for X-Road (Kansallinen Palveluväylä).

Requirements
------------

- Ubuntu 14.04 or later on target machine.
- The `python-passlib` package is required on the initiating machine.
- Inventory file should preferably use FQDN instead of IP as these are passed to
  a script that generates certificates per host. Variables are listed below for
  override purposes.

Role Variables
--------------

- `xroad_admin_fqdn` - FQDN for the admin Web UI certificate.
- `xroad_service_fqdn` - FQDN for the service certificate. If uncertain, use
   same as `xroad_admin_fqdn`.

Dependencies
------------

- https://git.forgeservicelab.fi/ansible-roles/kapa-secureserver/

License
-------

BSD

Author Information
------------------

Jukka Nousiainen

FORGE Service Lab
