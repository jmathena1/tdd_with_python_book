Provisioning a new site
======================

## Required Packages: 

* Git
* nginx
* Python 3.6
* venv + pip

eg, on Ubuntu

    sudo add-apt-repository ppa:deadsnakes/ppa
    sudo apt update
    sudo apt install git nginx python36 python3.6-venv

## Nginx Virtual Host config

* see nginx.template.conf
* replace DOMAIN with, e.g., staging.my-domain.com

## Folder structure

Assume we have a user account at /home/username

/home/username
|__ sites
     |-- DOMAIN1
     |    |-- .env
     |    |-- db.sqlite3
     |    |-- manage.py etc
     |    |-- static
     |    |-- venv
     |-- DOMAIN2
     |    |-- .env
     |    |-- db.sqlite3
     |    |-- etc
