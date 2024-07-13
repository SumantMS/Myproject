
# Myproject
To use your Java code with Eclipse and MySQL, follow these steps:

### Setting Up MySQL Database

1. Install MySQL: Ensure MySQL is installed on your system. You can download it from [MySQL Downloads](https://dev.mysql.com/downloads/).

2. Start MySQL Server: Start the MySQL server from the command line or using MySQL Workbench.

3. Create Database:
   - Open MySQL command line or MySQL Workbench.
   - Run the following SQL command to create your database:
     ```sql
     CREATE DATABASE course_management_system;
     ```

4. Create Tables:
   - Use MySQL command line or a client like MySQL Workbench to execute the SQL commands from your Java code to create tables (`Course`, `Student`, `Grade`).

### Setting Up Eclipse

1. Download and Install Eclipse: If not already installed, download Eclipse IDE from [Eclipse Downloads](https://www.eclipse.org/downloads/).

2. Set Up Java Project:
   - Open Eclipse IDE.
   - Create a new Java project (`File -> New -> Java Project`).
   - Give your project a name and click `Finish`.

3. Add MySQL JDBC Driver:
   - Download MySQL Connector/J from [MySQL Connector/J Downloads](https://dev.mysql.com/downloads/connector/j/).
   - Extract the downloaded file.
   - In Eclipse, right-click on your project -> `Build Path -> Configure Build Path`.
   - Click `Add External JARs...` and select `mysql-connector-java-x.x.xx.jar` from the extracted folder.
   - Click `Apply and Close`.

4. Write and Run Your Code:
   - Copy your Java code (like the one you previously provided for course management system) into a Java class within your Eclipse project.
   - Ensure your MySQL server is running.
   - Run your Java application (`Run -> Run As -> Java Application`).

### Running the Application

1. Navigate the Application:
   - Follow the console prompts in Eclipse to navigate through the menu options (Course Management, Student Management, etc.).

2. Interact with MySQL Database:
   - Ensure your Java application connects to the MySQL database (`course_management_system`) as specified in your JDBC URL (`jdbc:mysql://localhost:3306/course_management_system`).

3. Handle Database Operations:
   - Perform operations such as adding courses, registering students, assigning grades, etc., as per the menu options in your Java application.

By following these steps, you should be able to set up and run your Java application using Eclipse IDE with MySQL as the database backend.
