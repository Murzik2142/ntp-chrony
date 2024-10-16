Role chrony
=========

Install and configure chrony service 

Requirements
------------

ansible 3.1.2+\
ansible-galaxy 2.16.11+\
Not tested on earlier versions

Role Variables
--------------

None.

Dependencies
------------

user in sudoers 

Example Playbook
----------------

```
- name: Install and configure chrony service
  hosts: host
  become: yes
  roles:
    - chrony
```

License
-------

BSD-3-Clause

Author Information
------------------

Murzabaev Marat (murzik2142@gmail.com)