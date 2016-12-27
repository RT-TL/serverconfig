# Udacity Linux Server Configuration Project

This document contains

* [Server Access & Adresses](#server-access-&-addresses)
* [Server configuration](#server-configuration)

## Server Access & Adresses

* SSH-Port: 2200
* IP-Address: 35.161.208.242
* URL to app: http://35.161.208.242/


## Server configuration

Overview of the steps taken to configure the server.

### Software installation

* installed postgresql Database
* installed git version control system
* installed dependencies for item catalog app through th shell script included in the repository
* installed apache2 web-server
* updated software has been installed thorugh apt-get update/upgrade

### Web server configuration

* apache2 config was adjusted according to tutorial
* wsgi script created to serve python app
* configured postgresql database
* populated database through repository-included script
* enabled & configured uncomplicated firewall
* launched apache2 service

### Users and permissions

* created postgresql database
* created seperate user for postgresql database access
* created user grader
* allowed grader to use sudo
* enable ssh access for grader
* disable remote login for root user

### External dependencies & third party resources

* updated Facebook api settings to allow access from the server´s IP-address