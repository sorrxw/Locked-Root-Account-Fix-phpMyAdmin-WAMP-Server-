# Locked-Root-Account-Fix-phpMyAdmin-WAMP-Server-
Quick fix if you ever become an idiot and lock the root account on your phpMyAdmin

### Instructions ###

ini.sql (put this in your C drive)

Add below to the following directory or its equivalent on your system: C:\wamp64\bin\mysql\mysql8.2.0

[mysqld]
init-file=C:\\init.sql

Credit to these two threads: https://dba.stackexchange.com/questions/325329/unlock-the-only-mysql-account and https://dev.mysql.com/doc/refman/8.0/en/alter-user.html
