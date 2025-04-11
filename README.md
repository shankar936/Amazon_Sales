# Amazon Data Analysis using SQL 

## Overview 
This project involves a comprehensive analysis on "Amazon" dataset using SQL.The goal is to extract valuable insights from "Amazon" dataset on Product,Customer,Sales and answer the business questions based on the dataset.
The following Readme will provide all the information about the project.

## Dataset 
[Amazon dataset :]("C:\Users\Shankar\OneDrive\Documents\personal\sql\Amazon.csv")

## Schema 
create schema amazon;
use amazon ; 
``` sql 
drop table if exists sales; 
create table sales 
(
    	Invoiceid varchar(50),
        Branch varchar(50),
        city varchar(50),
        customertype varchar(50),
        gender varchar(20),
        productline varchar(40),
        unitPrice float, 
        quantity int,
        tax float ,
        total float,
        date varchar(50),
        time varchar(50),
        payment varchar(50),
        cogs float,
        grossmargin float ,
        grossincome float,
        rating float 
);


