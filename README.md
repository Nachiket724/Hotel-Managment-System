# Restaurant Menu Application
I have tried to computerize the hotel management system through my project. The project is written in Python 3 that uses the OOPS concept ie it is based on object and classes. The project minimizes the manual work of the employee of the hotel management team and store/modify the bill details of the customer.

## Requirements
Python-3 & MySQL.

## Changes in Code
### Sample Code

##### con=mysql.connector.connect( host="localhost", user="root", passwd="root", database="hotel")
                                
If you want to use one MySQL database or phpMyAdmin. Just make changes in (host=" YOUR_HOST"). 

Change (user="root") to (user="YOUR_MySQL_username") .

Change (passwd="root") to (user= "Your_MySQL_password").
 
 # Usage
 
 ### Download MySQL Community Server https://dev.mysql.com/downloads/windows/installer/8.0.html
 
 After Installing MySQL Community Server
 
 Open MySQL 8.0 Command Line Client and enter a password.
 
 Then Execute Query - CREATE DATABASE hotel ;
 
 Then download the Hotel Management System Project.
 
 ### git clone -- recursive https://github.com/Nachiket724/Hotel-Managment-System.git
  
After Downloading 
  
1.Open Project Folder.
 
2.Open CMD of that directory.
  
3. Then Type command python menu.py. (Customer will use this application.)
  
4. Open one more CMD of that directory.
  
5. Then Type command python hotel.py (Hotel staff will use this application.)
  
6. Then customer must log in into the application by reserving the table.
  
7. He/she can order the food by using this application.
  
8. After doing all the stuffs, e-bill is generated.
  
9. Simultaneously whatever the customer order's will automatically be shown in the CMD of Hotel Staff Computer.
  
  
  
