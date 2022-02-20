# Pewlett-Hackard-Analysis
Employee Database with SQL

## Purpose: 
The purpose of this assignment is to basically create and learn how to use an SQL database. Throughout this module and challenge we import and export large datasets into pgadmin and practice different methods of making tables in pgadmin and write multiple SQL statements

## Overview: 


After reviewing the employee files for Pewlett Hackard, we made an entity relationship diagram using QDD(quick database diagrams) to organize and gather elements from data tables. the data was imported using postgres and pgAdmin interface. The goal is to help the employers figure out how many people are retiring and how many employees are eligible to be mentored

 Employee database relationship diagram for Pewlett Hackard:
![QuickDBD-export](https://user-images.githubusercontent.com/96362530/154857092-f225f51f-706d-4def-8619-69b66d5f3a02.png)

## Results

  * With the first review of creating a list of potential "silver tsunamis," the query resulted in many duplicates due having multiple positions. 
  * Using the 'distinct on' SQL script, the duplicates were removed leaving the most recent job title to create a unique list of retiring employees. 
  * There were around 90,400 people that were looking to retire.
  * The mentor eligibility list had 1549 employees born in 1965

## Summary
### How many roles will need to be filled as the "silver tsunami" begins to make an impact?
There will have to be 90,398 people that will leave which will make a huge impact and in order to deal with that impact more people need to be hired and mentored

### Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

There are 1549 employees that are on the mentee list. 90,000 mentors can definitely help 1500 mentees. The main thing to point out here is that there is a big difference in numbers and that no managers met the mentor eligibility requirement.

### The tables below compare the counts by titles of the retiring and mentor eligible employees. 

![Screenshot_21](https://user-images.githubusercontent.com/96362530/154857605-8c3efd84-41a0-4d47-a385-ba7a4a549f64.png) ![Screenshot_22](https://user-images.githubusercontent.com/96362530/154857631-82146762-4859-46aa-85e7-a902ee29392e.png)





