# Webitel v22.12

## Install Ansible 2.10+ on Debian 11

Check Debian version

	lsb_release -d
	Description:    Debian GNU/Linux 11 (bullseye)

Install Ansible

	apt install git gnupg sudo ansible

Check Ansible version:

	ansible --version
	ansible 2.10.8

## Run ansible playbook for webitel

Install Webitel:

	ansible-playbook -i hosts/localhost playbook.yml
