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
    - hosts: servers
      roles:
         - { role: mds1455975151.ansible-tc-cli }
```
License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
