# impala-migrator

Impala table backup/restore

Impala is an open source massively parallel processing query engine runs on top of clustered systems like Apache Hadoop. 

This tool contains scripts for backup and restore impala tables. Both the scripts are written in python and is compatible only with python3 or later.

#Install Steps

Download the backup and restore scripts

#Usage
<br><br>
usage: impala-backup.py [-h] tablename

Backup impala databse tables

positional arguments:
```
  tablename Tablename
```
optional arguments:
```
  -h, --help show this help message and exit
```
<br><br>
usage: impala-restore.py [-h] tablename

Restore impala databse tables

positional arguments:
```
  tablename Tablename
```
optional arguments:
```
  -h, --help show this help message and exit
```
