Mailman
=========

Installs and configures Mailman with Exim4 on Debian systems.

Requirements
------------

None.

Role Variables
--------------

    mailman_language: default language for Mailman, e.g. en

    mailman_domain: domain name to use for mailman, e.g. lists.example.com 

Language to use for Mailman.

Dependencies
------------

apache (https://github.com/libraries-fi/ansible-role-apache)

Example Playbook
----------------

```
- hosts: mail
  roles:
    - role: mailman
      mailman_domain: lists.example.com
```

License
-------

MIT

Author Information
------------------

Libraries.fi
