# Registration-Form-using-Java-and-MySQL

This repository contains code and instructions on how to build a simple registration form using Java and MySQL.

## Requirements
- MySQL Workbench
- IDE (preferably Eclipse IDE)
- Java Development Kit (JDK)

## Steps -> MySQL
1. Open MySQL
2. Select Database Tab and select connect to Database and press ok
3. Enter password set during installation (remember the password)
4. Execute this query
```sql
create database myDatabase;
use myDatabase;
create table student(USERNAME varchar(30) not null,GENDER varchar(10) ,
FATHERS_NAME varchar(30) ,PASSWRD varchar(20),
CONFIRMPASSWRD varchar(20) ,CITY varchar(30),
EMAIL varchar(30) );
```
## Steps -> Eclipse
1. Open Eclipse and set up workspace
2. Create new Java Project
3. Open files /Main.java and /RegistrationForm.java
4. Right click project, select properties
5. Under libraries tab click on "Add External JARs"
6. Choose file /mysql-connector-j-8.0.31 and apply
7. Run the project

## Further Reading

<details>
<summary>References</summary>

[Swing Documentation](https://docs.oracle.com/javase/7/docs/api/javax/swing/package-summary.html)<br/>
[MySQL Connector Documentation](https://dev.mysql.com/doc/connector-j/8.0/en/)<br/>
[tutorialsfield](https://www.tutorialsfield.com/registration-form-in-java-with-database-connectivity/)
</details>
