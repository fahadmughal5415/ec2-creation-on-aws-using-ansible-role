Create EC2 Instance on AWS
=========

This Ansible role automates the process of creating EC2 instances on AWS using Ansible collections and Boto3. It provides a streamlined way to deploy and manage EC2 instances.

Requirements
------------

- Ansible version 2.1 or higher.
- AWS credentials configured on the system where Ansible is executed.
- Boto3 and botocore Python packages installed on the Ansible control node.

Role Variables
--------------

The following variables can be set in your playbook or passed as parameters:


Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
