# playbooks
Collection of Ansible Playbooks that I use to manage my servers.

# Update servers
`ansible-playbook -i inventory.ini update.yml -kK`

*Note: -kK will ask for password for ssh and root user.*