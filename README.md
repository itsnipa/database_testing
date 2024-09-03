# database_testing in classicmodels database

The 'classicmodels' database i have used to perform various database testing was taken from [here](https://www.mysqltutorial.org/getting-started-with-mysql/mysql-sample-database/) . This is mainly a sample database which will help you wrok with MySQL quickly and effectively.

The 'classicmodels' database is a retailer of scale models of classic cars. It contains typical business data, including information about customers, products, sales orders, sales order line items, and more.

We’ll use this sample database in our MySQL tutorials to demonstrate a wide range of MySQL features, from simple queries to complex stored procedures.

# Setup

# Database Setup
   
   
   1. Fork this repository
   
   2. Clone the repository in your project folder.

      ``` git clone https://github.com/itsnipa/database_testing.git ```
   
   3.  Download MySql from [here](https://dev.mysql.com/downloads/installer/) and install it.
   
   4.  Go to Mysql workbench and click on database to connect with the database.
   
   5.  Take a sql editor and Create a database

       ![image](https://github.com/user-attachments/assets/df8c97eb-932b-479a-9fd4-2c5846f58e90)
   
  
   6.  Then go to server and import "classicmodels.sql" in database
   
   8.  Select 'databasename' you gave in default target schema

       ![image](https://github.com/user-attachments/assets/a9755599-cdb2-4bd5-98ac-b9fdc6e1cd16)

   9. once you are done with importing files go back to database and  you will see the imported folders and files will be there in 
       "classicmodels" database

       ![image](https://github.com/user-attachments/assets/b0194195-e593-40a3-9666-72366dcc05a0)

   10. Before starting any operation; for connecting with database write
       ```use classicmodels(database_name)```
       to use database.


# Schema of Database Testing

   
   for testing 'schemas of the database' follow the steps given in the ```Database_Schema_Testcase_Writing.xlsx``` file which you have 
   already cloned.


   ![image](https://github.com/user-attachments/assets/d31f93bc-0d47-4aaf-a05e-041757131818)


# Stored procedure Testing


for stored procedure testing follow the ```Steps``` and then cross check results with  ```Test Query``` wheather the result from following 'Steps' is equal to test query or not.


   ![image](https://github.com/user-attachments/assets/1c4caf30-4dfb-4bc2-ad0d-ccc612adf0d3)


# Stored Function Testing


for stored function testing follow the ```Steps``` and ```Test Query```


![image](https://github.com/user-attachments/assets/dc8bb27f-e1ab-4964-a1b8-003089c75dd4)



# Data Integrity Testing


for data integrity testing  firstly you have to create database and  import the other sql file ```students_information.sql``` you have cloned. use the database, Now like before, follow ```Test Query``` given in ```data_integrity_testing.xlsx``` file to test the cases there in description


![image](https://github.com/user-attachments/assets/dedb9af2-9ec6-4586-86b7-ba19d11e3cfd)


   


 
