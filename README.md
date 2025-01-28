# playbooks
Collection of Ansible Playbooks that I use to manage my servers.

# Update servers
ansible-playbook -i inventory.ini update.yml --ask-become-pass -u USERNAME

use `-l GROUP` to limit to only a specific group inside the inventory.ini file.