Role Name
=========

This ansible role creates a redis container on target hosts

Requirements
------------

Docker and python's docker module must be present on target hosts

Role Variables
--------------

See [defaults](defaults/main.yml)

Example Playbook
----------------

```
- hosts: servers
  become: yes
  roles:
    - role: aboveops.ct_redis
```

License
-------

MIT
