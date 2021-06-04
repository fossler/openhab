# openHAB
Install OpenHAB on a debian based distro like RaspberryPi/Raspbian or ubuntu.


1. Modify inventory/main.yml to meet your needs
2. You may want to modify group_vars/all.yml
3. run: ansible-playbook playbook-install-openhab.yml -e"host=openhab"
