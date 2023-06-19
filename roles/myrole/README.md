Here I've uploaded the role which is used in my project to deploy the nginx application.

Playbook example:
- hosts: servers
  roles:
     - { role: username.rolename, x: 42 }
