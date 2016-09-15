User creation
=========

Simple role to create user accounts

Requirements
------------
None


Role Variables
--------------
- name: user login
- comment: long description
- shell: 
- groups: 
- append: yes by default
- password: 


Dependencies
------------
None


Example Playbook
----------------



    - hosts: servers
	  vars:
	    - name: myUser
		  shell: /bin/bash
		  groups: apache
		  password: *******
      roles:
         - { role: ansible-role-user}

License
-------

MIT / BSD

Author Information
------------------

Created by David Palomar