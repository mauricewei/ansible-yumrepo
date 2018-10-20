Role Name
=========

ansible-yumrepo

Requirements
------------

system: Centos 7.x
ansible version: 2.0 +

Role Variables
--------------

packages_dir: 安装包所在路径，默认/opt/packages

Dependencies
------------


Example Playbook
----------------

    - hosts: all 
      roles:
        - { role: ansible-yumrepo, packages_dir: /opt/packages }

License
-------

BSD

Author Information
------------------

by weimeng
