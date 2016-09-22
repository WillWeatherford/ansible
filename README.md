# Django Deployment

This repository contains ansible roles and playbooks which implement a basic
deployment of Django to an AWS ec2 instance.

command:

ansible-playbook -i path/to/inventory --private-key=path/to/privatekey.pem playbook_name.yml --extra-vars='@vars_file.tml'