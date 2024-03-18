Name: Leen Sobhia
Student ID: 101178141
Assignment 3 COMP3005

Assignment 3 Question 1:
This Read Me file contains instructions on how to use the code for interacting with a database containing a table with some data, and to retrieve/update/delete and add data
as required.
Along with this Read Me file, I have provided the SQL code to create the test table "students" as well as the code required to insert data into this table. Finally, the source
code written in Java is also provided.
The source code can be found in 

Requirements:
The provided Java code works with pgadmin4 for managing PostgreSQL databases.
1. The user is required to install and use pgadmin4 to interact with the databases. Create a new database (e.g. Assignment3), and within this database create a table (e.g. students).
2. An IDE environment such as IntelliJ to execute the provided source code. Refer to: https://jdbc.postgresql.org/ for installation instructions of pgJDBC to be able to interact with pgadmin4 using IntelliJ.
3. Copy and paste the provided source code into IntelliJ and simply compile and run/execute the code.
4. The code contains 5 functions plus a main function that contains the code for user interaction. The functions are:
	- getConnection
	- getAllStudents
	- addStudent
	- updateStudentEmail
	- deleteStudent

A description of the purpose of each function has been provided in the source code as comments. In summary, with the exception of getConnection, the 4 other functions utilize SQL statements in Java to interact with the "students" table to manipulate the data in pg4admin. The first function, getConnection, establishes a connection between IntelliJ and a database in pg4admin. 
5. Upon successful connection, and execution of the code, the user will prompted to interact with a menu with options to choose from:

	1. Get all students
	2. Add a student
	3. Update student email
	4. Delete a student
	5. Exit

The user may choose any option by entering a number 1-5 (exclusive) to interact with the application.
1. Get all students will print all the student data in the students table from the database
2. Add a student essentially inserts a student into the students table (the user will be required to enter first name, last name, e-mail, and the enrollment date (yyyy-mm-dd)
3. Update student email, updates an e-mail for a student with a specified student ID
4. Delete a student, deletes a student with a specified student ID

Video demonstration of the code and interaction with pg4admin:

https://youtu.be/Ak3Qgt3Rcl8
