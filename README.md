rails-provision
===============

[![Build Status](https://travis-ci.org/eendroroy/ansible-role-rails-provision.svg?branch=master)](https://travis-ci.org/eendroroy/ansible-role-rails-provision)

Ansible role to install rails-provision

Role Variables
--------------

Example:

```yml
deploy_user: deployer
deploy_home: /home/deployer
app_name: application
app_env: production

rubies:
  - vevrsion: 2.4.0
```

Supported OS
------------

- Ubuntu
    - precise (12.04)
    - saucy (13.10)
    - trusty (14.04)
    - xenial (16.04) - xenial requires python2 to be installed for ansible support

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: eendroroy.rails-provision }

License
-------

MIT

Author Information
------------------

**Indrajit Roy** - *owner* - [eendroroy](https://github.com/eendroroy)