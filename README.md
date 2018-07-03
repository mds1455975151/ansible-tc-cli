Qcloud CLI role for Ansible
=========

Installs and configures the qcloud cli for qcloud service such as CVM

Requirements
------------
- Ansible 2.0+
- Test CentOS 7.x

Role Variables
--------------
The default variables are as follows:
```
tccli_out_format: 'json'
tccli_region: 'ap-guangzhou'
tccli_access_key_id: ''
tccli_secret_access_key: ''
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
```
- hosts: all
  roles:
    - role: 'mds1455975151.ansible_tc_cli'
      tccli_access_key_id: 'xx'
      tccli_secret_access_key: 'xx'
      tccli_region: 'xx'
```
License
-------

BSD

Author Information
------------------

1455975151@qq.com
