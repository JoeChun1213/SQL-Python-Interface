# Interfacing SQL with Python


## Objective
In this project, we aim to create a python front-end interface for SQL databases and demonstrate
sophasticated database management achieved via the inteface.

## Resources
 
- Software: SQL, Python

## Info:

In particular, we created the following user-interface:

  ++ WELCOME to SQL query. ++
Please choose one query from the list below:
1. Creating databases
2. Creating tables
3. Insert/Delete rows in a tables
4. Query
5. Alter table
6. Drop table 
7. Quit  

## Highlights and Example

While the traditional queries are based on manually inputting the entire query by the user, our front-end  system achieves the same via  forming the query using python statements based on the options provided by the user. This is the hightlight of our interface. In short, we made this interface for layman. One who do not know anything about the database or the list of available database would find our interface more user-friendly. Below is one example showcasing our interface by a layman.  

Enter your choice:   4
The following databaseses are available for query
['information_schema', 'mysql', 'performance_schema', 'sys', 'Test', 'Test1', 'university']

Which database would you like to access? university

 Your database is selected and it is ready for query!!! 

The following tables are available in your university database
Showing tables
['Club', 'Course', 'Enrollment', 'Faculty', 'Offering', 'StdClub', 'Student', 'Student1']

Which table would you like to access? Student
The following columns are available for query

['StdNo', 'StdFirstName', 'StdLastName', 'StdCity', 'StdState', 'StdZip', 'StdMajor', 'StdClass', 'StdGPA']

Which column would you like to see? (seperate the column name by comma)   StdNo, StdFirstName, StdGPA

Enter the where condition if any .., 
Enter groupby condition if there is one  
Enter the orderby condition if any .., 

select StdNo, StdFirstName, StdGPA from Student


        StdNo  StdFirstName  StdGPA
0. 123456789         HOMER     3.0
1. 124567890           BOB     2.7
2. 234567890         CANDY     3.5
3. 345678901         WALLY     2.8
4. 456789012           JOE     3.2
5. 567890123        MARIAH     3.6
6. 678901234          TESS     3.3
7. 789012345       ROBERTO     2.5
8. 876543210    CRISTOPHER     4.0
9. 890123456          LUKE     2.2
10  901234567       WILLIAM     3.8

Do you want to continue Y or N: N
