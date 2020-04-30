# web2py_ansible_playbook
An Ansible playbook to install web2py on Ubuntu 20.04

## How to install
 1. Install Ubuntu 20.04
 1. Create ssh key
 1. copy-ssh-id to your new server
 1. ssh to new server to ensure you can connect without any passwords or prompts
 1. Update the variables at the top of the yaml file for:
    1. ansible_user - this should be the user on your ubuntu server
    1. web2py_password - this is the password for the admin console to be used in web2py
 1. cd to ansible playbook directory
    * PYTHON3 run `ansible-playbook -i hosts web2py-install.yaml -bK`
    * PYTHON2 run `ansible-playbook -i hosts web2py-install-2.yaml -bK`
 1. Enter 'become' password
 1. Watch the server install

This playbook was based on the setup-web2py-nginx-uwsgi-ubuntu.sh install script included in web2py with help from a script posted by Clemens.

Please contact me with any changes, ommissions or suggestions.
