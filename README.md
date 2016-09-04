Minikube Installation Role
=========

This role summarizes all the directions of
[the latest Minikube release installtion notes](https://github.com/kubernetes/minikube/releases/tag/v0.9.0)
in one little role. The purpose of it is to automate deployment of my solution which is closely based on having Kubernetes.

Requirements
------------

Any more or less Debian-like Linux will do as a host. Ansible shall be installed also.

Role Variables
--------------

Currently there is nothing to customize in this role

Dependencies
------------

No dependencies on other roles currently exist

Example Playbook
----------------

You could use this role this way:

    - hosts: servers
      roles:
         - { role: Sulion.minikube_role }

License
-------

MIT

Author Information
------------------

I am what I am.
