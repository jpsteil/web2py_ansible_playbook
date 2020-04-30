# web2py_ansible_playbook
An Ansible playbook to install web2py on Ubuntu 20.04

## How to install
 1. Install Ubuntu 20.04
 1. Create ssh key
 1. copy-ssh-id to your new server
 1. ssh to new server to ensure you can connect without any passwords or prompts
 1. cd to ansible playbook directory
    1. PYTHON3 run `ansible-playbook -i hosts web2py-install.yaml -bK`
    1. PYTHON2 run `ansible-playbook -i hosts web2py-install-2.yaml -bK`
 1. Enter 'become' password
 1. Watch the server install
