Role Name
=========

Adds target host to IPA as client

Requirements
------------

None

Role Variables
--------------

theforeman_custom_aide_for_audit_tools_ipaadmin_principal - principal name who is eligible to enroll new client servers on IPA
theforeman_custom_aide_for_audit_tools_ipaadmin_password - principal password

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: theforeman.freeipa_client_add, ipaadmin_principal: principal_username, ipaadmin_password: principal_password }

Use ansible-vault to encrypt passwords

License
-------

GPL2

Author Information
------------------

khain
