# Simpris
Python Django MySQL Project Management System

Simpris is a general purpose project management system which is designed to be used to manage many different types of projects. Over the years Simpris has groen into a multifaceted project with the following technologies:

## Front End
Bootstrap v3 and v5
JQuery
React
VueJS
JQuery DataTables

The system uses the MySQL database thought there is an early stage branch for use with PostGres.

Code will soon be released for Simpris under the GNU license.

## How to set up Simpris
### 1. Create database
- Create a MySQL database called simpris or similar
- Either:
    - Run Django migrations against the database objects
- Or:
  - From the scripts in the Database-Objects-MySQL folder
    - Build the tables 
    - Build the views
    - Build the stored procedures
    - Build the functions

### 2. Populate the lookup tables
Use MySQL Workbench or similar to import data from files in the DataLoad folder:
- lookup-type.csv
- lookup.csv
 
### 3. Create Django superuser
If not already done create the Django superuser in the normal way

### 4. Deploy the Django code
- Configure SendGrid or other email provider
- Configure database connection
- Start managing your projects!
