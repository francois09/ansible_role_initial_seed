initial_seed
============

Initial setup of an hypervisor or a simple VM. This includes packages install,
backports, upgrade mechanism, and some strange things like convert /LVM to
a real LVM space.

This role handles Debian from Buster

Requirements
------------

-

Role default variables
----------------------

-

Dependencies
------------

-

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: initial_seed
	   default_user: root # use default popped up user

License
-------

BSD

Author Information
------------------

François TOURDE
