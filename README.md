# MySql
HOW TO INSTALL MYSQL ON CentOS
--------------------------------------
-> Install the database application
-> Start and stop the database service
-> Start the mysql shell
-> Set the root password
-> View users
-> Create a database
-> Manage users and permissions
-> Summary

# Install MySQL

Install the MySQL database through the CentOS package manager (yum) by running the following commands at a command prompt:

 sudo yum install mysql-server
 sudo /sbin/service mysqld start
 
 # Run the following command:

 sudo /usr/bin/mysql_secure_installation

Press Enter to give no password for root when prompted for it.

To apply some reasonable security to your new MySQL server answer yes to all the prompts. 
In order, those prompts enable you set the root password,
remove anonymous users, disable remote root logins, delete the test database that the installer included, 
and then reload the privileges so that your changes will take effect.

