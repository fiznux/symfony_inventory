inventory
=========

a simple inventory/stock management web application that can perform simple CRUD (create, read, update and delete) operations

How to use : 

System Required :
	- PHP >= 5.6 
	- Mysql
	- pdo_mysql

Dump inventory.sql to your mysql DB

Open inventory/app/config/parameters.yml , adjust the following to fit your mysql settings

	database_host: your_mysql_host
    database_port: null
    database_name: inventory
    database_user: your_mysql_user
    database_password: your_mysql_password
	
Browse the url : http://localhost/inventory/web/item/
