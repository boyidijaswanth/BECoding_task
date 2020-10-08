# BECoding_task

Task:- 
Develop a CRUD (Create – Read – Update – Delete) application using CodeIgniter PHP REST framework in this round. Basically, you will use FreshSales CRM API to create a Contact in FreshSales CRM, Retrieve Contact, Update Contact, Delete Contact. 

Also simultaneously  create a MySQL database and table called ‘contacts’ and then perform similar Write, Read, Update and Delete operations.
Prerequisites:- CodeIgniter - 3, PHP > 7 and MySQL > 5
OS:- Windows 10

This application will have 4 apis which are addContact,getContact,updateContact and deleteContact.
addContact :- The REST method POST creates a contact either in CRM or in database.This endpoint will accept data in JSON format.

getContact:- The REST method GET returns the JSON formatted data of a contact.

updateContact:- The REST method POST updates the existing record either on CRM or database. This endpoint will accept data in JSON format.

deleteContact:- The REST method POST deletes the existing record either from CRM or database. This endpoint will accepts data in JSON format

DB SCHEMA CREATION:-

Created contacts table inside smatbot database.queries to create the database and table are:

To create database:- create database smatbot;

To create table:- create table contacts (
    id int auto_increment primary key,
    first_name varchar(200) not null,
    last_name varchar(200) not null,
    email varchar(200) not null,
    mobile_number int(10) null
);
