

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
The goal of this project is to remap variables during extraction data from the source table to the target table.<br />
The mapping process is controlled by a control dictionary in which the variables that are subject to the process are indicated.

The processor fetches the table and variables specified in the control dictionary, checks the structure of the target table, and converts the variable types to match the new fields.
  
  
## Technologies
Project is created with SAS BASE version 9.4.

	
## Setup
Code can run in both SAS Studio and SAS Enterprise Guide.<br />
To be able to test the code download the code file (.sas) and the control dictionary file (xmlx). Then add them to your SAS environment.


