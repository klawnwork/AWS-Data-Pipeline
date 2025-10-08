# AWS-Data-Pipeline
Transforms column labels in a .csv file, moves the file from S3 to a MicrosoftSQL server via a Glue job and multiple Lambda functions using PySpark

<h2>Languages and Utilities</h2>

- <b>Python</b> 
- <b>SQL</b>
- <b>Powershell and sqlcmd- tested SQL server connectivity</b>
- <b>Docker- created a local environment to debug persistent ODBC driver errors ocurring in Lambda</b>
- <b>Microsoft ODBC Configuration Files and Driver(odbc.ini, odbcinst.ini, libmsodbcsql-18.5.so.1.1)- connected Lambda to the SQL Server </b>
- <b>SQL Server Management Studio- managed the SQL server, set login method</b>

<h2>Environments</h2>

- <b>AWS Cloud- S3, EC2, VPC, Lambda, Glue, Secrets Manager, IAM</b>
- <b>SQL Server 2022 Express</b>
- <b>SQL Server Configuration Manager- configured TCP/IP, set port 1433, and enabled SQL Server Browser for remote connctions</b>
- <b>Docker Desktop- tested ODBC configurations in a local environment</b>
- <b>Linux- sourced libraries and ODBC driver/config files, tested network connectivity to SQL server</b>
- <b>Windows 11- Local OS</b>
- <b>VSCode- created and debugged Python scripts</b>

<h2>Project Architecture</h2>

<p align="center">
<br />
<img width="816" height="351" alt="Screenshot 2025-09-04 133111" src="https://github.com/user-attachments/assets/7b8a90cc-e7a8-4ee2-ad97-7b17fe812e0c" />

<h2>Project Walkthrough</h2>

<b>Full video walkthrough here:</b>
<b>https://youtu.be/mKFMrlFzjyk<b>
