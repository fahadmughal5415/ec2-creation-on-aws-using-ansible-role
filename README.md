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
- instance_type: The type of EC2 instance to launch. Defaults to `t2.micro`.
- region: The AWS region where the EC2 instance will be created. Defaults to `us-east-1`.
- image_id: The IMAGE ID to used for the instance.

Note:
All of the above variables are already declared in the ec2/defaults/main.yml.

Dependencies
------------

This role does not have any dependencies on other Ansible roles.

Example Playbook
----------------

    - hosts: localhost
      connection: local
      roles:
         - ec2

License
-------

GPL-2.0-or-later

Author Information
------------------

Fahad Mughal - DevOps Engineer at BDPhone.com
