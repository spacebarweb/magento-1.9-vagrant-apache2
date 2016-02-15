# Vagrantfile with pre-loaded Magento 1.9

## Requirements

* [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
* [Vagrant](https://www.vagrantup.com/downloads.html)

## How start

Clone this repository and go to the root directory.

Start the VM: `vagrant up`

Now you can access to your Magento : `http://magento.dev`

For custom config you can edit the `puphpet/config.yaml`: `vim ./puphpet/config.yaml`

## MySQL

You need to use an SSH connection.

With the information below you can connect to the MySQL server running on the virtual machine.

## Default information

* SSH User: vagrant
* SSH Pass: vagrant
* SSH Port: 2222 (default by vagrant)
* MySQL Host: 127.0.0.1
* MySQL Port: 3306
* MySQL User: magento
* MySQL Pass: magento
* Db Name: magento

## Packages

Following installed:

* apache2
* mysql-server
* mysql-client
* php5.6
* vim
* git
