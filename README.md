# AWS-Data-Pipeline
Transforms column labels within a .csv file, moves the file from S3 to a MicrosoftSQL server via a Glue job and multiple Lambda functions using PySpark

<h2>Languages and Utilities </h2>

- <b>Python</b> 
- <b>SQL</b>
- <b>Powershell and sqlcmd- tested SQL server connectivity</b>
- <b>Docker- created a local environment to debug persistent ODBC driver errors ocurring in Lambda</b>
- <b>Microsoft ODBC Configuration Files and Driver(odbc.ini, odbcinst.ini, libmsodbcsql-18.5.so.1.1)- connected Lambda to the SQL Server </b>
- <b>SQL Server Management Studio- managed the SQL server, set login method</b>

<h2>Environments </h2>

- <b>AWS Cloud- S3, EC2, VPC, Lambda, Glue, Secrets Manager, IAM</b>
- <b>SQL Server 2022 Express</b>
- <b>SQL Server Configuration Manager- enabled TCP/IP, set port 1433, and enable SQL Server Browser for remote connctions</b>
- <b>Docker Desktop- tested ODBC configurations in a local environment</b>
- <b>Windows 11- Local OS</b>
- <b>VSCode- created and debugged Python scripts</b>

<h2>Project Architecture:</h2>

<p align="center">
<img src="https://imgur.com/ZeB9Pu4.png" height="80%" width="80%"/>
