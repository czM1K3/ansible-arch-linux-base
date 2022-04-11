# Arch Linux base installation with Ansible
This repo contains basic installation of Arch Linux with Ansible to Virtual machine

## Steps
- Run on target:
	```bash
	passwd # By default it looks for "toor"
	systemctl restart sshd
	```
- Change parameters in vm.yml
- Run:
	```bash
	sh start.sh
	```
- Default password is *toor*