Role Name
=========

nakahiro386.apt

ansible role apt for ubuntu

Requirements
------------

* python-apt (python 2)
* python3-apt (python 3)

Role Variables
--------------

see ./defaults/main.yml

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: nakahiro386.apt
      become: yes
```

License
-------

MIT

