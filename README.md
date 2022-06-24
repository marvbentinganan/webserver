# Introduction

This is an Ansible Playbook that will automate the **creation** and **provisioning** of a server to deploy web applications.

## What's included

* Update the Server to latest version and install security updates.

* PHP

* Composer

* Git

* Golang

* Nodejs

* Python + Pip

* Redis

* MySQL

* PostgreSQL

* Nginx

* Let's Encrypt

* Supervisor

* Firewall

* Security Updates

## Usage

1. Clone this repository into your machine with Ansible installed.

2. Create a `hosts` file. A sample hosts file is included in this repo.

3. Update the variables file located inside `global_vars/main.yaml`. If you are using this playbook to automate server creation, set your cloud provider variables inside `global_vars/cloud.yaml`.

4. Provision your server. `ansible-playbook -i hosts setup.yaml`.
