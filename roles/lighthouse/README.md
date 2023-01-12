Ansible-Role Lighthouse for CentOS 7
=========

Role installs Lighthouse on CentOS 7. 

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

* The git repo of lighthouse to install.
  ```yml
  lighthouse_vcs: https://github.com/VKCOM/lighthouse.git
  ```

Dependencies
------------

You must first perform the role!

```yaml
- name: nginx
  src: git@github.com:PanMonsters/roles_nginx.git
  scm: git
```
This role will install nginx required for lighthouse to work!

Example Playbook
----------------

The simpliest example:
```yaml
- name: Install Lighthouse
  hosts: lighthouse
  roles:
    - lighthouse
```

License
-------

MIT

Author Information
------------------

HW_netolgy.

