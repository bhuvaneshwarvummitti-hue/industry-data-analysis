# Data Cleaning and Preprocessing of Layoffs Dataset Using SQL
This repo contains a begginer -friendly industry data analysis project done in excel and SQL

# Tools used
-Database: MySQL
-Language: SQL

# Project Overview
This  project focuses on cleaning and preparing a raw layoffs dataset using MySQL. The goal is to transform inconsistent and unclean data into a structured, reliable dataset suitable for analysis and visualization. The project follows a systematic data-cleaning workflow, including duplicate removal, data standardization, handling missing values, correcting data types, and removing unnecessary columns.

# What I learned
Create staging tables to preserve the original dataset.
Identify and remove duplicate records using ROW_NUMBER() and window functions.
Standardize inconsistent text values using functions like TRIM() and UPDATE.
Convert text-based dates into SQL DATE format using STR_TO_DATE().
Handle missing and null values by updating or replacing incomplete records.
Use self-joins to fill missing information from related records.


