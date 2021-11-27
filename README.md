 # README

 > **NAME**

How to create and connect MySQL Database?

 > **DESCRIPTION**
This will help you to learn how to use MYSQL create database statement to create a new database on a MySQL database server.
[Reference](https://www.mysqltutorial.org/mysql-create-database)


  > **VISUAL**

![DATABASE](https://www.mysqltutorial.org/wp-content/uploads/2018/09/MySQL-CREATE-DATABASE-new-connection.png)
![PHP](https://www.mysqltutorial.org/wp-content/uploads/2018/09/MySQL-CREATE-DATABASE-connection-name.png)
  > ***Installation**

{
	Step 1 -	Download MySQL WorkBench
	Choose the latest MySQL WorkBench and select to download.
}

{

    	Step 2 - installing
	Once you downloaded MySQL WorkBench you can install it onto your computer
}

{

    	Step 3 - Setup my SQL WorkBench
	- First, launch the MySQL Workbench and click the setup new connection
    	- Second, type the name for the connection and click the Test Connection button.
	- MySQL Workbench displays a dialog asking for the password of the root user:
	- You need to (1) type the password for the root user, (2) check the Save password in vault, and (3) click OK button.
	- Third, double-click the connection name Local to connect to the MySQL Server.
	- MySQL Workbench opens the following window which consists of four parts: Navigator, Query, Information, and Output.
	- Fourth, click the create a new schema in the connected server button from the toolbar:
	- In MySQL, the schema is the synonym for the database. Creating a new schema also means creating a new database.
	- Fifth, the following window is open. You need to (1) enter the schema name, (2) change the character set and collation if necessary, and click the Apply button:
	- Sixth, MySQL Workbench opens the following window that displays the SQL script which will be executed. Note that the CREATE SCHEMA statement command has the same effect as the CREATE DATABASE statement.
	- If everything is fine, you will see the new database created and showed in the schemas tab of the Navigator section.
	- Seventh, to select the testdb2 database, (1) right-click the database name and (2) choose Set as Default Schema menu item:
	- The testdb2 node is open as shown in the following screenshot.
	- Now, you can work with testdb2 from the MySQL Workbench.

}
> **AUTHOR**

Author Name: Kieth Lawrence Fresnillo



