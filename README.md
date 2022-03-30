#Taxi Service Web App
___________________________________________________________________________
This is a simple Web Application that simulates the work of a taxi service. 
The program can authenticate users, work with data of drivers, cars, 
car manufacturers and work with the database.  
___________________________________________________________________________
####Your steps for successful usage of the App:
1. Config the **Apache Tomcat** version **9.0.xx**;
2. In the **log4j2.xml** file in the line 7 change the path **_"logs\app.log"_** 
to your absolute local path;
3. Recommended to use **JDK 11** version;
4. Replace stubs in **taxi/util/ConnectionUtil.java** with your real values; 
5. Run Tomcat Server;
6. Click on "Register" on the login page and create a new driver profile;
7. After you have been redirected to the login page, log in using the new login and password;
8. And now you have access to all features of the program;
___________________________________________________________________________
####The following features are available for use:
1. **_Display all drivers_** allows you to display all drivers from the database and to delete
drivers one by one;
2. **_Display All Cars_** allows you to display all cars from the database and to delete
cars one by one;
3. **_Display All Manufacturers_** allows you to display all car manufacturers from the database 
and to delete manufacturers one by one;
4. **_Display All My Cars_** allows you to display a list of all cars that are assigned to you as 
a driver and the ability to remove them from the list;
5. **_Create new Driver_** - you can register a new driver in a database also the feature 
is available to unregistered users;
6. **_Create new Car_** - you can add a new car to a database;
7. **_Create new Manufacturer_** - you can add a new manufacturer to a database;
8. **_Add Driver to Car_** - this section allows you to add a driver to the list of car drivers.
