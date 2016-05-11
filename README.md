Ansible Playbook for Simple Backups
===================================

Simple and very basic Ansible Playbook for backups tested in DigitalOcean VPS server. This is an alpha quality software and is subject to change, use it under your own risk.

## Requirements

In the controller machine:

* Ansible

In the managed machine:

* ssh access
* mysql-python

## Instructions

* Configure it by modifying the `vars.yml` file
* How to run it: `$ ansible-playbook -i inventory/hosts siteBackup.yml`

You can filter by tags:

* `databases` To backup only databases
* `folders` To backup only folders

## License

[MIT](./LICENSE).
