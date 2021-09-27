[![CI](https://github.com/penguinperk/ansible_role_ibm_terrform_provider/actions/workflows/ci.yml/badge.svg)](https://github.com/penguinperk/ansible_role_ibm_terrform_provider/actions/workflows/ci.yml)

Role Name
=========

ansible_role_ibm_terrform_provider

IBM Cloud Terraform Provider Version
------------
 Version 1.31.0


Requirements
------------

At this point this only runs on Linux (MacOS, Redhat, CentOS Ubuntu, Debian, etc..). 
I will get it running on Windows. 

Role Variables
--------------

Current default:
provider_path:      ~/.IBM_terraform
terraformplugin:    ~/.terraform/plugins/



Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: terraform
      roles:
        - { role: penguinperk.ansible_role_ibm_terrform_provider }

License
-------

BSD-3-Clause

Author Information
------------------

This project was created by Scott Perkins
