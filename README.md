# Banking Insurance
This project is to track and identify the creditcard defaulters and define the insurance premium
according to the list of defaulters by joining data from insurance system, creditcard systems, state
code fixed width data and the customer master datasets. 
## Getting Started
 - Install VMware 15 player 
 - Install centos
 - Install requirements
 - Start Services
 - Run the scripts
## Local Installation
Install tools given in requirements.txt

**Make sure you have the following installed:**
- Hadoop
- Sqoop
- Hive
- Hbase
- Phoenix
- Zookeeper

**Installing mysql & postgresql**
- [mysql](https://www.digitalocean.com/community/tutorials/how-to-install-mysql-on-centos-7).
- [postgresql](https://linuxize.com/post/how-to-install-postgresql-on-centos-7/).
## Starting services 
- Hadoop
  - start-all.sh 
  - mr-jobhistory-daemon.sh start historyserver (job history server)
- Mysql service
  - service mysqld start
- Hive metastore in a terminal
  - hive --service metastore & (as background service)
- Hbase
  - start-hbase.sh 
- Zookeeper
  - zkServer.sh start
- Phoenix
  - sqlline.py localhost
## Run the scripts
   Generate reports from the final table
