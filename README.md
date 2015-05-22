[![Codeship Status for midonet/ansible-midonet-repos](https://codeship.com/projects/3e024f00-e2b4-0132-4034-0ebe16c39f2d/status?branch=master)](https://www.codeship.io/projects/81530)

Role Name
=========

Ansible playbook for midonet OSS repositories.

Installation
------------

This role requires at least Ansible v1.6

    ansible-galaxy install abelboldu.midonet-repos

Role Variables
--------------

Default variables:

    --

    midonet_version   : current
    midonet_release   : stable
    openstack_version : juno
    plugin_release    : stable


Example Playbook
----------------

    - hosts: server
      roles:
         - role: abelboldu.ansible-repos
		   midonet_version: 2015.03

License
-------

Apache 2.0

