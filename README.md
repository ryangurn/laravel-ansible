# Ansible Playbook - Laravel

## Setup

Before running this playbook it seems imperitive to load the various roles that we use. Please run the list of commands below on the control node to ensure the roles have been loaded properly.

```bash

ansible-galaxy role install geerlingguy.php
ansible-galaxy role install geerlingguy.php-versions
ansible-galaxy role install geerlingguy.repo-remi
ansible-galaxy role install geerlingguy.apache
ansible-galaxy role install geerlingguy.apache-php-fpm

ansible-galaxy role install geerlingguy.php-mysql
ansible-galaxy role install geerlingguy.mysql

ansible-galaxy role install geerlingguy.php-memcached
ansible-galaxy role install geerlingguy.memcached

ansible-galaxy role install geerlingguy.php-redis
ansible-galaxy role install geerlingguy.redis

ansible-galaxy role install geerlingguy.pip
ansible-galaxy role install geerlingguy.supervisor

ansible-galaxy role install geerlingguy.nodejs

```