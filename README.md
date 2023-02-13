# Ansible Playbook for reclaim oled volume (mounted on /var/oled) for more space in root volume on Oracle Linux 9 

ansible-playbook playbook.yml -i hostname, --private-key id_rsa --ssh-extra-args "-o StrictHostKeyChecking=false"
