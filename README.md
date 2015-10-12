# Catalog App

Catalog App keeps your items well organized.

## Table of contents

- [Dependencies](#dependencies)
- [Installation](#installation)

## Dependencies
As a first step, make sure you have the following dependencies installed:
- [Python 2.7.x](https://www.python.org/downloads/)
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [Vagrant](https://www.vagrantup.com/downloads.html)

On the links above you'll find the necessary documentation to install each one of the required dependencies.

## Installation

1. [Download the latest version](https://github.com/jlulloav/catalog-app/archive/master.zip).
2. From the vagrant folder, you can run this command to start the virtual machine:
```$ vagrant up```
3. Run this command to go inside the virtual machine:
```$ vagrant ssh```
5. Run these commands to start the application:
```$ python /vagrant/catalog/database_setup.py```
```$ python /vagrant/catalog/db_feed.py```
```$ cd /vagrant/catalog/```
```$ python application.py```
6. Open web browser and open this url [http://localhost:8000/] (http://localhost:8000/)