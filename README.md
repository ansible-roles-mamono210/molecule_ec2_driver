[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/molecule_test_ec2.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/molecule_test_ec2)

Role Description
=========

Create and destroy EC2 resources.

Requirements
------------

None

Role Variables
--------------

See details in 'meta/argument_specs.yml'.

Dependencies
------------

None

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - molecule_test_ec2
```

License
-------

BSD
