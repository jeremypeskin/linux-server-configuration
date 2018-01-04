# linux-server-configuration
Baseline installation of a Linux server hosting a Flask web application.
* Public IP: http://18.217.112.161/
* SSH Port: 2200

## Software Installed
* apache2: Linux Web Server
* Finger Displays user info
* Flask: Python framework
* Git: Distributed version control system
* mod-wsgi: Apache module for hosting python applications
* ntp Synchronizes server times
* pip: Python package manager
* Postgresql: Database
* psychopg2: postgresql adapter for python
* SQLAlchemy: SQL Object Relational mapper for python

## Configuration Changes
* Updated packages
* Changed the SSH port from 22 to 2200
* Configured UFW to allow incoming connections for SSH, HTTP, and NTP
* Created a new user called Grader with sudo permission and SSH key pair
* Cloned and setup your Item Catalog from Github (changed application.py to __init__.py and moved the backend from Sqlite to Postgresql)
