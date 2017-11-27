Role Name
=========

Recreates a VM that has already been created.

Requirements
------------


Role Variables
--------------
osp_recreate_vm:
  api:
    auth:
      auth_url: "http://192.168.0.1:35357/v.20"
      username: "admin"
      password: "{{ keystone_admin_password }}"
      project_name: "admin"
    auth_type: "password"
    endpoint_type: "admin"
    region_name: "RegionOne"
    keystone_version: "2"
    projecT_name: "admin"
  vm:
    - vm1:
        name:
        image:
        key_name:
        flavor:
        region_name:
        availability_zone:
        key_name:
        flavor:
        security_groups:
        auto_ip:
        server:
        image:                             

Dependencies
------------


Example Playbook
----------------


License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
