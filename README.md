# Online-Course-Registration-System--JavaApplet-and-sql-
Database Management System mini Project 

This was developed in NetBeans. 

It is Java Applet powered with localhost sql database connection.

Its main class is Login.java

To Manage admin its Username is admin and password is admin123.
To change that change if statement if(Username.getText().matches("//Admin Username//") && Password.getText().matches("//admin Password//"))
in Login.java

The Database is Considered as :

1. COURSES
          Column 1 : CID        Type : Integer
          Column 2 : COURSENAME Type : varchar(50)
   
2. COURSE_STUDENT
          Column 1 : USERNAME Type : varchar(50)
          Column 2 : COURSES  Type : varchar(255)

3. LOGIN
          Column 1 : SID      Type : Integer
          Column 2 : USERNAME Type : varchar(50)
          Column 3 : PASSWORD Type : varchar(50)

4. STUDENT
          Column 1 : SID          Type : Integer
          Column 2 : STUDENTNAME  Type : varchar(50)
        
        
If you want to add or remove columns please do required changes in source code.

I have Considered Student can register for 5 Courses you can change accordingly.
