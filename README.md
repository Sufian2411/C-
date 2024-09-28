Basic CRUD Application with C# and MSSQL This project is a basic CRUD (Create, Read, Update, Delete) application developed using C# with Windows Forms as the user interface. It allows users to manage records in a database by performing the four basic operations on data: adding new records, retrieving/displaying records, updating existing records, and deleting records.
🚀 Key Features Create: Add new records to the database through an input form. Read: Display existing records in a table or list. Update: Modify details of existing records. Delete: Remove records from the system. Show: To display data in GridView.
🛠️ Tools and Technologies Programming Language: C# User Interface: Windows Forms (WinForms) Database: Microsoft SQL Server IDE: Visual Studio ADO.NET: for database connectivity and operations
🛠️ Project Workflow User Interface (Windows Forms)
Main Form: Contains buttons for Create, Edit, Read, Update, Delete, and Refresh operations, along with a DataGridView to display records. Add/Edit Form: A separate form to enter or modify record details. Message Boxes: Used for confirming actions such as deletion or record creation. Database Operations
Create: Add a new record by submitting a form. Read: Fetch and display records from the database in the DataGridView. Update: Edit an existing record by selecting it and submitting the modified data. Delete: Remove a record by selecting it and confirming deletion. Show: To display data in GridView.
⚙️ Technical Steps
Demonstration Video:https://youtu.be/iv5IVw2uLWA?feature=shared
Here’s an updated README.md file, reflecting the instructions on how to import the .bacpac file from the project repository.
📥 Importing the .bacpac File
The .bacpac file for the database has been uploaded to this repository. You can import this file into your local SQL Server instance using the following steps:
Steps to Import the .bacpac File:
Download the .bacpac file
Navigate to the repository where the .bacpac file is located.
Download the file to your local machine.
Open SQL Server Management Studio (SSMS)
Launch SQL Server Management Studio to work with SQL Server databases.
Import the .bacpac file
In SSMS, right-click on Databases in the Object Explorer.
Select Import Data-tier Application.
Follow the Import Wizard
Click Next in the wizard.
Select the Import from local disk option.
Browse to the downloaded .bacpac file.
Follow the prompts to import the database and assign it a name.
Update the Connection String in Your C# Project
After importing the database, make sure to update the connection string in your C# project to reflect the newly restored database:
SqlConnection conn = new SqlConnection(@"Data Source=MSI\SQLEXPRESS;Initial Catalog=""Crud Operation"";Integrated Security=True;");
Run the Project
Once the connection string is properly set up, run the project to interact with the database and perform the CRUD operations.
 
YouTube
CRUD Operations using c# with MSSQL.
MD. ABU SUFIAN SHOWROV
17 views · 14 days ago
Open
Share in meeting
