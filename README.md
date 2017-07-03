Ansible Role: Terraform
=========

[![Build Status](https://travis-ci.org/michalschott/ansible-role-terraform.svg?branch=master)](https://travis-ci.org/michalschott/ansible-role-terraform)

Installs Terraform on Linux amd64.

This role downloads Terraform from Hashicorp website, checks checksum and installs it in your system.

Requirements
------------

None.

Role Variables
--------------

Default variables:
```
terraform_version: 0.8.8
terraform_checksum: "sha256:403d65b8a728b8dffcdd829262b57949bce9748b91f2e82dfd6d61692236b376"
terraform_path: /usr/local/bin
terraform_owner: root
terraform_group: root
```

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: terraform }

License
-------

MIT

Author Information
------------------

This role was created in 2017 by [Michal Schott](http://github.com/michalschott).
