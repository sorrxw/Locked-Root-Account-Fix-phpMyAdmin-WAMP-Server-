# Locked-Root-Account-Fix-phpMyAdmin-WAMP-Server-
Quick fix if you ever become an idiot and lock the root account on your phpMyAdmin

### Instructions ###

ini.sql (put this in your C drive)

Add below to the following directory or its equivalent on your system: C:\wamp64\bin\mysql\mysql8.2.0

[mysqld]
init-file=C:\\init.sql
