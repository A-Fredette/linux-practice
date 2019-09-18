# linux-practice

### Server IP Address: 34.200.214.95

### SSH Port: 2200

### URL of hosted application:  http://34.200.214.95/

## Linux Configutation Changes

This project is build with AWS Lightsail and Ubuntu 18.04.3 LTS. This linux instance was configured for security and stability by:

* Prohibiting root remote access
* Enabling a firewall that disables all incoming connections, with the exception of: SSH (port 2200), HTTP (port 80), and NTP (port 123) -- Note that SFTP port was enabled for development, but it currently disabled.
* Enforicing key-based authentication


## Summary of Software Installed

This application makes use of apache, wsgi and several python libraries, most notably:

apache 2
wsgi
flask
sqlalchemy
oauth2client
httplib2
sqlite

## Resources

Several online resources were used to complete this project, including:

BogoToBogo's Tutorial on Ubunutu/Flask/WSGI:
https://www.bogotobogo.com/python/Flask/Python_Flask_HelloWorld_App_with_Apache_WSGI_Ubuntu14.php

Poftut's Guide of UFW:
https://www.poftut.com/how-to-start-stop-and-enable-disable-iptables-or-ufw-in-ubuntu-debian-kali-mint/

Udacity FullStack Nanodegree Knowledge Base


## Public SSH Key

The public SSH key is located in /grader_key
