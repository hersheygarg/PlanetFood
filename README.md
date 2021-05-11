# PlanetFood
Planet Food is basically a restaurant's management application. The main objective of the project is to computerize the paper work in restaurants. 
It consists of an admin panel and a cashier panel. Admin panel is used by the manager to manage the employees and cashiers, add categories and items to 
the restaurant menu and monitor date wise sales. The cashier panel is used by cashier to take orders and generate bills. Talking about the technical aspects of the 
project, the application is developed on java platform and implements the concepts of java database connectivity(jdbc), collections, exception handling and 
multithreading and Oracle has been used as the database management system.  The application is divided into 4 packages : data access objects(DAO), 
Plain old java objects(pojo), dbutil and gui. Gui package contains all the front end related frames which are visible to the end user. 
dbutil package contains code which establishes the connection between the application and the database. 
DAO package contains all the functions which implements business logic. These functions retrive and send data to the database. 
POJO package contains classes which are used to hold data of different entites related to the project like employees, products, categories etc. 
The main idea behind dividing the project into packages was to seperate business logic, data and the front end for easy code management.

#Setting up the project
Import the zip file in any editor.
Oracle database is needed for this project.
After installing oracle, create the corresponding database by looking into the dbutil file.
Create the required tables by looking into pojo package.


