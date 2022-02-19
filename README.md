# crud operation php mysql!

The project is written in php8.1. MySQL selected as database.

To work with this project, you will need to install the following tools: XMAPP.

- git clone the repository

Unzip the folder, then move it to C:\xampp\htdocs.
Start XAMPP, then Apache and MySQL.

- Create Database in phpMyAdmin:

create database name "collegedb"
create table using given below sql statement

```sh
CREATE TABLE `students` (
`id` int(11) NOT NULL AUTO_INCREMENT,
`first_name` varchar(30) NOT NULL,
`last_name` varchar(30) DEFAULT NULL,
`gender` varchar(10) DEFAULT NULL,
`email` varchar(50) DEFAULT NULL,
`course` varchar(20) DEFAULT NULL,
PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=1 DEFAULT CHARSET=latin1
```

### Run the Project

Run the localhost (Apache service)
point to the:

```sh
http://localhost/crud

```
