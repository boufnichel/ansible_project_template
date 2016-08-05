Role Name
=========

# Ansible project template role
[![Build Status](https://travis-ci.org/boufnichel/ansible_project_template.svg?branch=master)](https://travis-ci.org/boufnichel/ansible_project_template)

This role allow ansible newbies to create a standard project structure as explain below
> [Ansible best practices ](http://docs.ansible.com/ansible/playbooks_best_practices.html)

Requirements
------------

none

Role Variables
--------------
```
bpath = the path of where the role structure will be generated (default=/mnt/ansible_project/)
brole = the name of the generated role (default=common)
```

Dependencies
------------
none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
- hosts: hybris
  roles:
    - { role: boufnichel.project_template, bpath: '/mnt/devops-project', brole: 'plateform' }
```

License
-------

GNU General Public License v3.0

Author Information
------------------
[Github](https://github.com/boufnichel)

[Linkedin](https://ma.linkedin.com/in/mohamed-boufnichel-a81a7aa1)



