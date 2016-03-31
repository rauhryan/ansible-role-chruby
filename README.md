# Ansible Role: Install chruby
[![Build Status](https://travis-ci.org/ferrarimarco/ansible-role-chruby.svg?branch=master)](https://travis-ci.org/ferrarimarco/ansible-role-chruby)

An Ansible role that installs chruby.

## Using the role
### Installation
```
ansible-galaxy install ferrarimarco.chruby
```

### Variables
```
chruby_version: 0.3.9
```

### Example Playbook
```
  - hosts: all
    roles:
      - ferrarimarco.chruby
```
