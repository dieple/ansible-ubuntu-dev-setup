Ansible Ubuntu Dev PC setup
=========================

Ansible playbook for a quick and effortless installation of all essential and often used software for a web development

## Supported OS:

* Ubuntu 14.04+ based x86_64 (64bit) OS only !

## Quick start

* `curl -s https://raw.githubusercontent.com/dieple/ansible-ubuntu-dev-setup/master/run.sh | bash /dev/stdin prepare`
* **Check the `main.yml` file to see what will be installed. Check/modify version numbers and included roles**
* `ansible-playbook ~/ansible-ubuntu-dev-setup/main.yml --ask-sudo-pass`
