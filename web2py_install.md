# Install web2py on Ubuntu 20.04 with Ansible

 1. Install Ubuntu 20.04
 2. Create ssh key
 3. copy-ssh-id to your new server
 4. ssh to new server to ensure you can connect without any passwords or prompts
 5. cd to ansible playbook directory
 6. run `ansible-playbook -i hosts web2py-install.yaml -bK`
 7. Enter 'become' password
 8. Watch the server install
 