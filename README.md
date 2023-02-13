# Ansible Playbook for reclaim oled volume (mounted on /var/oled) for more space in root volume on Oracle Linux 9 

For local host:
1. ansible-playbook playbook.yml -i localhost, --connection=local

For remote host:
1. ansible-playbook playbook.yml -i hostname, --private-key ssh.key
