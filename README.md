# hello-world
Tutorial repository

Learning how to code and manage codes in the cloud.


Preparation of Synology

Install Web Station
configure nginx and php 7.0 as defaults
enable all libraries

install phyMyAdmin

Configure Synology implementation of MariaBD, as the default port for mysqld is 3307 and Joomla is looking for 3306 as the mysqld port. 
The default location for my.cnf for MariaDB is located at,
/usr/local/mariadb10/etc/mysql

Joomla
Note: Joomla files downloaded from official site doesn't work with Synology. Installing Joomla from Synolog Control center with Apache 2.2 installed, allow Joomla configuration to complete.
