# Car Pooling Database
This repository contains the final project of the **Database** course (AY 17/18) at *University of Naples Federico II*. 

## Assignment
The aim of the project is to develop a relational database for a nationwide car-pooling system, using Oracle Database 11g XE.

## Project
The project, developed in team of 3, is structured as following:
-  [design](https://github.com/fabiod20/database/tree/main/design) directory contains the **Entity-Relationship (ER) models** developed during the logical design of the database.
- [implementation](https://github.com/fabiod20/database/tree/main/implementation) directory contains the sql code used to develop end test the database. The code is organised in the following files:
  - *01_tablespace_and_dba.sql*: create the table space and the Database Administrator (DBA) user;
  - *02_roles_and_users.sql*: create **roles** and **users** of the database (drivers and passengers);
  - *03_tables.sql*: create **tables** of the database (drivers, passengers, cars, cities, trips, etc.);
  - *04_referential_integrity_constraints.sql*: create **referential integrity constraints** among the tables;
  - *05_triggers_and_procedures.sql*: create **triggers** and **stored procedures**;
  - *06_test_data.sql*: populate the database with some test data;
  - *07_queries.sql*: execute **queries** on the database.
- [documentation](https://github.com/fabiod20/database/tree/main/documentation) directory contains an exhaustive documentation of the system and its development, written in Italian.

