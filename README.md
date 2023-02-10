# Ansible Playbook for reclaiming oled volume (mounted on /var/oled) on Oracle Linux 9 for more space in root volume

For local host:
1. ansible-playbook reclaim-oled-volume.yml -i localhost, -c=local

For remote host:
1. ansible-playbook reclaim-oled-volume.yml -i hostname,
