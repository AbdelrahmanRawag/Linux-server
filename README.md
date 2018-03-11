# Project name:  
====================
Linux Server : You will take a baseline installation of a Linux server and prepare it to host your web applications. You will secure your server from a number of attack vectors, install and configure a database server, and deploy one of your existing web applications onto it.

# Configuration steps:  

* Add user grader to sudo group
* Update all currently installed packages
* Set-up SSH keys for user grader
* Disable root login
* Change timezone to UTC
* Add SSH port 2200
* Firewall Configuration
* Install Apache to serve a Python mod_wsgi application
* Install and configure the PostgreSQL database system
* Create a PostgreSQL role named catalog and a database named catalog
* Install Flask, SQLAlchemy
* Install Git
* Clone the repository that contains Item Catalog application
* Configure the Catalog application
* Configure Google OAuth
* Configure the web application to connect to the PostgreSQL database instead of a SQLite database
* Configure the Database to connect to the PostgreSQL database instead of a SQLite database
* Configure Apache to serve the web application using WSGI
* Restart Apache

  # How to run it:  
  * ssh connection: ssh grader@52.59.209.215 -p 2200 -i ~/.ssh/rsa_id
  * Item Catalog link: http://52.59.209.215.xip.io
