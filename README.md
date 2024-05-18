# MySQL Brute Force
A Python Program that uses **mysql-connector-python** module to brute force MySQL Server
## Requirements
Language Used = Python3<br />
Modules/Packages used:
* mysql.connector
* datetime
* optparse
* colorama
* multiprocessing
* time
<!-- -->
Install the dependencies:
```bash
pip install -r requirements.txt
```
## Arguments
* '-s', "--server" : Target MySQL Server
* '-p', "--port" : Port of Target MySQL Server (Default=3306)
* '-u', "--users" : Target Users (seperated by ',') or File containing List of Users
* '-P', "--password" : Passwords (seperated by ',') or File containing List of Passwords
* '-c', "--credentials" : Name of File containing Credentials in format ({user}:{password})
* '-w', "--write" : CSV File to Dump Successful Logins (default=current data and time)