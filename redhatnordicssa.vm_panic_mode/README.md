Role Name
=========

This role puts a virtual machine into lockdown, cutting all incoming and outgoing network communication using firewalld's panic mode.

Requirements
------------

System has RPM firwalld installed or is registered to a yum repository containing firewalld.

Role Variables
--------------

local_check_user: "string"

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      vars:
        local_check_user: something
      roles:
         - { role: redhatnordicssa.vm_panic_mode }

License
-------

GPL 3.0

Author Information
------------------

Red Hat Nordics Solution Architecture team
