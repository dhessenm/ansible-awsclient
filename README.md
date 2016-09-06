Ansible role: awsclient
=========

Role installs aws client and creates aws config file

Requirements
------------

Role Variables
--------------

Available variables are listed below, along with default values:

role specific:
* aws_cli_user: vagrant
* aws_cli_user_home: /home/vagrant
* aws_output_format: 'json'
* aws_region: 'eu-central-1'
* aws_access_key_id: 'YOUR_ACCESS_KEY_ID'
* aws_secret_access_key: 'YOUR_SECRET_ACCESS_KEY'

Dependencies
------------

* proxyconf

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: awsclient }

License
-------

BSD

Author Information
------------------
it's me

