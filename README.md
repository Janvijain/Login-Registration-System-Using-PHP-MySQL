# Form To Perform CRUD operations using PHP & MySQL and styled using HTML & CSS.
Hello Everyone created a simple form using PhP and MySQL to perform the following operations
1.Create
2.Read
3.Update
4.Delete

SQL script to create database and table is present is test.sql file

Create Database -> test

CREATE TABLE `form` (
  `id` int(11) NOT NULL,
  `name` varchar(250) NOT NULL,
  `contact` bigint(10) NOT NULL
) 

Output Images are attached for references
img1- Store & Retrieve Data.
img2 - Edit & Delete Data Of a particular 'id'.

Storing data in the database and retrieving it in the table.
Data can be edited and deleted by using 'id' as a reference from database.
If you perform operations you will notice onclicking Edit , 'Save' button is changed to 'Update' button.
