## **SQL & MySQL Assignment: Lab-1** 

### **1. What is SQL and Its Use?** 

**SQL, or Structured Query Language, is the standard language used to communicate with relational database systems. It allows users to store, manipulate, and retrieve data efficiently. The primary purpose of SQL is to provide a consistent way to manage large sets of structured information.** 

##### **Its uses include:** 

- **Data Retrieval: Extracting specific information from large datasets using queries.** 

- **Data Manipulation: Adding new records, updating existing ones, or deleting unnecessary data.** 

- **Database Definition: Creating and modifying tables, schemas, and other structures.** 

- **Access Control: Granting or revoking permissions to ensure data security.** 

- **Transaction Management: Ensuring data consistency and reliability when multiple operations are performed.** 

### **2.Describe all the different commands of SQL, mention** 

### **use of it and syntax.** 

**SQL commands are broadly divided into categories based on their purpose:** 

- **Data Definition Language (DDL): These commands define and modify the structure of the database.** 

**CREATE is used to create new tables or databases. Example:** 

**sql CREATE TABLE Students (ID INT, Name VARCHAR(50));** 

- **ALTER modifies the structure of an existing table, such as adding a new column.** 

##### **sql ALTER TABLE Students ADD Age INT;** 

**■ DROP deletes a table or database permanently.** 

##### **sql DROP TABLE Students;** 

- **Data Manipulation Language (DML): These commands handle the actual data inside tables.** 

**INSERT adds new records.** 

**sql INSERT INTO Students VALUES (1, 'Lakshay', 20);** 

**■ UPDATE modifies existing records.** 

**sql UPDATE Students SET Age = 21 WHERE ID = 1;** 

**■ DELETE removes records.** 

**sql DELETE FROM Students WHERE ID = 1;** 

- **Data Query Language (DQL):** 

**SELECT retrieves data from tables.** 

**sql SELECT Name, Age FROM Students WHERE Age > 18;** 

- **Transaction Control Language (TCL): These commands manage transactions to ensure data integrity.** 

   - **COMMIT saves changes permanently.** 

   - **ROLLBACK undoes changes made in the current transaction.** 

   - **SAVEPOINT sets a checkpoint within a transaction.** 

- **Data Control Language (DCL): These commands manage user privileges.** 

   - **GRANT provides access rights.** 

   - **REVOKE removes access rights.** 

###### General Availability (GA) Releases 

###### Archives 

~Y/ 

#### MySQL Installer 8.0.35 

8 Note: MySQL 8.0 is the final series with MySQL Installer. As of MySQL 8.1, use a MySQL product's MSI or Zip archive for installation. MySQL Server 8.1 and higher also bundle MySQL Configurator, a tool that helps configure MySQL Server. 

Select Version: 

Select Operating System: 

Windows (x86, 32-bit), MSI Installer 8.0.35 2.1M (mysql-installer-web-community-8.0.35.0.msi) MDS; 214dF2ced#B3ebSede6ea7e115792406 | Signature Windows (x86, 32-bit), MSI Installer 8.0.35 288.6M (mysql-installer.community.8.0.35.0.msi) MDS: 2¢fda448a2971b6b5323775ef9e8d012 | Signature 

# © MySQL Community Downloads 

Login Now or Sign Up for a free account. 

An Oracle Web Account provides you with the following advantages: 



<!-- Start of picture text -->
« Fast access to MySQL software downloads<br>« Download technical White Papers and Presentations<br>» Post messages in the MySQL Discussion Forums<br><!-- End of picture text -->



<!-- Start of picture text -->
« Report and track bugs in the MySQL bug system<br><!-- End of picture text -->



<!-- Start of picture text -->
Login » Sign Up »<br>using my Oracle Web account for an Oracle Web account<br><!-- End of picture text -->

MySQL.com is using Oracle SSO for authentication. If you already have an Oracle Web account, click the Login link. Otherwise, you can signup for a free account by clicking the Sign Up link and following the instructions. 

No thanks, just start my download. 



<!-- Start of picture text -->
MySQL. Installer Check Requirements<br>Adding Community<br>The following products have failing requirements. MySQL Installer will atternpt to resolve<br>ther automatically, Requirements marked as manual cannot be resolved automatically. Click<br>on each item to try and resolve it manually.<br>ED pen eseneae For Product Requirement Status<br>© MySQL for Visual Studio 1.2.10 Visual Studio version 2015, 2017 or 2... Manual<br>Requirement Details<br>This is a manual requirement. You can attempt to resolve the requirement using the<br>information provided. When done, you can press the Check button to see if the<br>requirment has been met.<br>Requirement: Visual Studio version 2015, 2017 or 2019 must be installed.<br>Check<br>< Back Cancel<br><!-- End of picture text -->



<!-- Start of picture text -->
MySQL. Installer Installation<br>Adding Community<br>The following products will be installed,<br>Product ‘Status Progress Notes<br>@ J mysat server8.0.29 Complete<br>asian @ EJ mysat workbench 80.29 Complete<br>@ EJ mysat shen 2.0.29 Complete<br>@ [QJ mysat Router 8.0.29 Complete<br>@ [Ee] connectorvonsc 8.0.29 Complete<br>i) Ey) Connector/C ++ £0.29 Complete<br>@ E] Connector/J 8.0.29 Complete<br>a E] Connector/NET 8.0.29 Complete<br>7]E>] Connector/Python 8.0.29 Complete<br>i) {=} MySOL Documentation 8.0.29 Complete<br>i)[=] Samples and Examples 80.29 Complete<br>Show Details ><br><!-- End of picture text -->



<!-- Start of picture text -->
MySQL. Installer Connect To Server<br>Samples and Examples<br>Select the MySOL server instances from the list to recerve sample schermas and data.<br>yninect To Server [ Server Port Arch... Type Status ]<br>GB MySOL Server 8.0.29 3306 X64 Stand-alone Server (ERBRRRESSREDEEEEGEEny<br>Provide the credentials that should be used (requires root prnaleges)<br>Click “Check” to ensure they work.<br>User name: — Credentials provided in Server configuration<br>Password: s#*sssssessssse<br>{ Check ] ol<br><!-- End of picture text -->



<!-- Start of picture text -->
MySQL. Installer Accounts and Roles<br>MuCOlMySQL ServerServer 8.0.2920 20 Root Account Password<br>Enter the password for the root account. Please rermember to store this password in a secure<br>place.<br>MySQL Root Password: eecccoessceoes<br>Repeat Password: Seeeseesreseece<br>Password strength: Strong<br>MySQL User Accounts<br>Create MySQL user accounts for your users and applications. Assign a role to the user that<br>consists of 3 set of prrvileges<br>MySQL User Name Host User Role Add User<br>Eait é<br>< Back Cancel<br><!-- End of picture text -->



<!-- Start of picture text -->
~<br>MySQL. Installer Installation Complete<br>Adding Community<br>The installation procedure has been completed.<br>Copy Log to Clipboard<br>@ Start MySQL Workbench after setup<br>© Start MySQL Shell after setup<br>The MySOL Shell is an advanced MySQL client application that can be used to work with<br>nstallation Complete single MySQL Server instances, Further, it can be used to create and manage InnoDB<br>Cluster, an integrated solution for high availability and scalability of MySOL databases,<br>without requiring advanced MySQL expertise,<br>[ terete Chester |<br>Refer to the following links for documentation, tutorials and examples on MySQL Shell:<br>MySOL Shell Documentation Setting up 9 Real World Cluster Blog<br>The All New MySOL InnoDB ReplicaSet Blog Changing Cluster Options Live Blog<br><!-- End of picture text -->

