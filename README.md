Ansible Role
============
------------

Roles provide a framework for fully independent, or interdependent collections of variables, tasks, files, templates, and modules. In Ansible, the role is the primary mechanism for breaking a playbook into multiple files. This simplifies writing complex playbooks, and it makes them easier to reuse.

Requirements
------------

You need to uncomment the below line in the ansible config file ($vi /etc/ansible/ansible.cfg) before creating a role.

roles_path    = /etc/ansible/roles

Then go to /ect/ansible/roles ($cd /ect/ansible/roles/) and create ansible galaxy with the role name ($ansible-galaxy init lamp).
Here I gave lamp.

Ansible Galaxy
--------------

Ansible Galaxy refers to the Galaxy website where users can share roles, and to a command line tool for installing, creating and managing roles.

-To list all available Roles

$ansible-galaxy list

-To list Contents of the Role

$tree lamp/<role name>
