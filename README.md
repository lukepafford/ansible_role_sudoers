Sudoers
=========
Requires no configuration.

Configures sudoers with the default settings.

Members of the wheel group can use sudo without a password,
and there is no instance of 'requiretty' in the configuration

Example Playbook
----------------
    - hosts: servers
      roles:
         - sudoers

License
-------

BSD
