ansible aws-cli
===============
[![Build Status](https://travis-ci.org/ypsman/ansible-aws-cli.svg?branch=master)](https://travis-ci.org/ypsman/ansible-aws-cli)

Installs python-pip and the awscli. <br>
Working on Debian and Ubuntu. <br>

Example Playbook
----------------

    - hosts: all
      roles:
        - role: ypsman.aws-cli
