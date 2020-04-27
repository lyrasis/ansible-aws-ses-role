Ansible Role - AWS SES
=========

Ansible Role that configures a server to use the AWS Simple Email Service (SES).
Currently only tested against Postfix on EC2 instances running Ubuntu Xenial (16.x).

Requirements
------------

You must have SES set up and properly authorized in your AWS account.
See https://docs.aws.amazon.com/ses/latest/DeveloperGuide/quick-start.html

Role Variables
--------------

See [defaults](./defaults/main.yml) for documented example of variables.

Dependencies
------------

None

Example Playbook
----------------

See [tests](./tests/test.yml) for an example playbook
NOTE: this role must be run with `become: true`

License
-------

CC0
