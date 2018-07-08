# certbot-ansible-role
Ansible role to install LetsEncrypt's certificates on Ubuntu using CertBot

Pre-requisites:
  * Nginx installed
  * App being served on the given hostname (deploy_server_hostname in vars/default.yml)

Steps:
  * Clone this repo
  * Include this into your playbook
  * Fill in details in vars/default.yml
  * Run the playbook
  * See the green secure mark on your site url and feel Happy ;)



