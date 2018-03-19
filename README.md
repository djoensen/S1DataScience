# S1DataScience
Shared files from presentations given by SentryOne's Data Science team.

Link to SentryOne:  https://www.sentryone.com/

List of helpful tips for setting up Microsoft Machine Learning Services:

1.	Here is a link to the SQL Server Setup guide on Microsoft.com
  	https://docs.microsoft.com/en-us/sql/advanced-analytics/r/set-up-sql-server-r-services-in-database

2.	If you run into any issues, check here
	  https://docs.microsoft.com/en-us/sql/advanced-analytics/known-issues-for-sql-server-machine-learning-services

3.	Using SQL Server Configuration Manager, make sure that the “SQL Launchpad” services is running
    - Also, verify that the correct account credentials are entered (I believe the account must have System Admin access to the SQL Server that ML Services is installed on)

4.	Here’s a helpful link for upgrading an existing installation of ML Services
    https://docs.microsoft.com/en-us/sql/advanced-analytics/r/use-sqlbindr-exe-to-upgrade-an-instance-of-sql-server

5.	This links to an excellent tutorial on SP_Execute_External_Script
   	https://www.mssqltips.com/sqlservertip/4747/sql-server-spexecuteexternalscript-stored-procedure-examples/
