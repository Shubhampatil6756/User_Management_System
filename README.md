# __User Management System__

User Management System is a Java application built using Maven and the SpringBoot framework.

---
## Table of Contents

- [Frameworks and Language Used](#frameworks-and-language-used)
- [Dataflow](#dataflow)
- [Data Structure](#data-structure)
- [Project Summary](#project-summary)
------
## Frameworks and Language Used

- __Java__ : The primary programming language used for developing the application.
- __Maven__ : A build automation tool and dependency management tool used for managing the project's dependencies and building the application.
- __SpringBoot__ : A powerful and widely used framework for building Java-based enterprise applications. It provides features like inversion of control, dependency injection, and seamless integration with various other libraries.
----
## Dataflow
* #### __Controller__ :
  In controller class I have exposed APIs for each operation like addUser , getUser , getAllUsers , updateUserInfo and deleteUser.

* #### __Service__ : 
   In Service class I have written the logic for each of API method and return it.

* #### __Repository__ : 
    In Repository class I have acchieved dependency injection for to get list of users from the Beanfactory which is basically a configuration class.

* #### __DataBase Design__ : 
     For to store deta of users I have used Arraylist as I feel it is easy to manupulate over Arraylist.
-----
## Data Structure

I have used Arraylist to maintain the list of users as It is easy to manupulate over Arraylist than other deta structures.

 ---------
## Project Summary

I have created a project User Management System. Which is basically used to maintain information of users. I have exposed APIs like to addUser , getUser , getListOfUsers ,  updateInfoOfUser incase we put wrong information and deleteUser if we want to delete the deta of any user.
