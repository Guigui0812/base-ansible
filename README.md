Base Role
=========

This role does basic configuration tasks that are meant to be done on all servers :

- Install troubleshooting tools
- Setup motd

Requirements
------------

- [Ansible](https://www.ansible.com/) - Ansible must be installed to execute the playbook.


Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: servers
  become: yes
  roles:
    - base-role
```

License
-------

BSD