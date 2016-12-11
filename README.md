Role Name
=========

[![Build Status](https://travis-ci.org/patrick-hill/ansible-role-whatpulse.svg?branch=master)](https://travis-ci.org/patrick-hill/ansible-role-whatpulse)
[![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-patrick--hill.whatpulse-blue.svg)](https://galaxy.ansible.com/patrick-hill/whatpulse)


Installs [WhatPulse](https://whatpulse.org/) on Debian based OS

Requirements
------------

Ansible 2.0+

Role Variables
--------------

    os_username
"os_username" is the target username that will be running whatpulse

    whatpulse_install_dir
"whatpulse_install_dir" is the directory where WhatPulse is installed

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: development-machines
      roles:
        - { role: patrick-hill.whatpulse}

License
-------

BSD

Author Information
------------------

Role written in 2016 by [Patrick Hill](http://www.HillsPCWorld.com) 
