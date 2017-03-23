# MySql
# Install MySQL

 sudo yum install mysql-server
 
 sudo /sbin/service mysqld start
 
 sudo /usr/bin/mysql_secure_installation

# Hive with Mysql metastore configure

$> cd /opt/software/hive/bin
$> ./schematool -initSchema -dbType mysql

Note: you will get message like below

Metastore connection URL:        jdbc:mysql://NN1.local:3306/hivemetadb?createDatabaseIfNotExist=true

Metastore Connection Driver :    com.mysql.jdbc.Driver

Metastore connection User:       root

Starting metastore schema initialization to 2.1.0

Initialization script hive-schema-2.1.0.mysql.sql

Initialization script completed

schemaTool completed

