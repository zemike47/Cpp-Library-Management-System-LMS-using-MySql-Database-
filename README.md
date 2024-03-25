# Cpp-Library-Management-System-LMS-using-MySql-Database-
**This C++ Library Management System utilizes a database-based approach for efficient management of library resources. It includes functionalities for managing student, admin, and book records within a MySQL database. If you encounter any issues connecting to the MySQL server, follow the steps below:
Steps to Run the Code (Windows)**

 Download Dev-C++ IDE:
        Download and install Dev-C++ IDE from [here](https://sourceforge.net/projects/orwelldevcpp/)

Connect MySQL with Dev-C++:
        Follow the steps outlined in this tutorial: [MySQL Connection Tutorial](https://youtu.be/B8fdzMTnOLc?si=vrWY8XO-phULyYNE) to set up MySQL connection with Dev-C++.


 Copy Source Code:
 
        Copy the source code provided in LMS.cpp.

    Paste Source Code:
    
        Open the Dev-C++ IDE and create a new file (.dev) as instructed in the tutorial.
        Paste the copied source code into this .dev file.

    Insert Database Server Password:
    
        Locate the line in the code: char pass[] = "password";
        Replace "password" with your actual MySQL database server password.

    Set Up Database:
    
        Open MySQL Workbench or any other.
        Import the Library.sql file provided.
        Execute the queries to create the necessary tables (student, admin, books).
        Once done, refresh the schema to ensure the library_database is displayed with the three tables.

    Run the Code:
    
        Go back to the Dev-C++ IDE.
        Compile and run the code.

Note:

    Ensure that your MySQL server is running before executing the code.
    Make sure to provide the correct database server credentials and password in the code.
    For any further assistance, refer to the provided tutorial or reach out for support.

       
