ansible-role-goaws
=========

Installs (goaws)[https://github.com/p4tin/goaws] binary to /usr/local/bin and create a system.d service `goaws`

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

```
tomtomau_goaws:
  version: 0.3.1
```


Example Playbook
----------------
```
    - hosts: servers
      roles:
         - { role: tomtomau.goaws }
```

License
-------

BSD

