# Wuzzuf
Wuzzuf is a well-known career mathcing website. ( https://wuzzuf.net/jobs/egypt )

This repository is a dektop application that imitates Wuzzuf.

### Technologies
* Database Management System: Oracle Database
* C# .NET framework
* C# ODP.NET library
* SAP Crystal Reports

### Functionalities
A User:
- Can be either an employer or an emplyee (job seeker)
- Can sign up / login and log out with their credentials (stored in the Database)

An Employer:
- Can view / Edit their profile data
- Can Add / Edit job ADs
- View the incoming applications on their job ADs
- Accept / Reject the applicant
- Optionally, add some comment with the acceptance / rejection that goes to the job seeker as a notification

A job Seeker:
- Can view / Edit their profile data
- Can see incoming notification about their applications
- Search for a job / Internship from a set of job categories
- Apply for a job

### How to use it ?
Make sure to run it on a MicroSoft Windows machine.
Make sure to download Oracle Database on your device and make a database called "orcl".
Make a connection to this database called "hr" with the password "hr" using Oracle SQL Developer.

Download the following:
- MiroSoft Visual Studio Installer
- MicroSoft Visual Studio 2019 -> https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Enterprise&rel=16&src=myvs
- make sure to include the .NET Core in the installation
- SAP Crystal Reports -> https://origin-az.softwaredownloads.sap.com/public/file/0020000001649932022
- Run the SQL Script from file "SQL_script.txt" in the program SQL Developer.
- open the solution file "wuzzuf.sln" with visual studio, hit run, and enjoy.

### Contact Development Team
- Ahmed Aboalesaad -> https://www.linkedin.com/in/ahmed-aboalesaad-3a352323b/
- Mahmoud Sayed    -> Mahmoud_smha@hotmail.com
- Yousef Faisal    -> https://www.linkedin.com/in/yousef-faisal/
