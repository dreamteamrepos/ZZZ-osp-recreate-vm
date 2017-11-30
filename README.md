Role Name
=========

Recreates a VM that has already been created.
Module doc http://docs.ansible.com/ansible/latest/os_server_action_module.html
Requirements
------------


Role Variables
--------------
```
osp_recreate_vm:
  api:
    auth:
      auth_url: "http://192.168.0.1:35357/v.20"
      username: "admin"
      password: "{{ keystone_admin_password }}"
      project_name: "admin"
      user_domain_name: "Default"
    auth_type: "password"
    endpoint_type: "admin"
    region_name: "RegionOne"
    keystone_version: "2"
    projecT_name: "admin"
  vm:
    test:
      action: rebuild            # The action you want to take with the VM. In this case it Will be rebuild.
      server: test               # Name of the Sever to recreate
      image: hadoop              # Name or ID of the Image

    other_vm:
      action:
      server:
      image:
```
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
