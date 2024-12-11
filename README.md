Role Name
=========

Nagios NRPE for checking k8s nodes, control and worker.

Requirements
------------

NRPE is already installed

Role Variables
--------------

- *libdir*: sub directory of /usr where lib files are installed
- *include_dir*: Fully qualified path of nrpe.d directory

Dependencies
------------

*role_nrpe* to install/configure NRPE

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: k8s
      roles:
         - role: arikkert.npre_k8s

License
-------

BSD

Author Information
------------------

    ARK-ICT
    Andre Rikkert de Koe - ICT
