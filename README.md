ansible-percona-mysql 5.6 for Ubuntu
============

Ansible role for installing Percona Mysql 5.6.

You can technically install other version if you change a few variables on `defaults/main.yml`. 

## Overwriting Variables

The `vars/main.yml` file should contain your list of packages you want to install in order to override defaults found in `defaults/main.yml`. Additionally, you can overwrite the variables as part of your playbook.

