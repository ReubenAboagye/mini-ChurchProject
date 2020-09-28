# mini-ChurchProject
Copy the folder "Data" to Disk C
the read format should be like "C:\\Data"

to allow a successful backup and restore database.

if restoring backup fails, execute  this query in sql window using MASTER

*setting database to single user mode after backup error*

<code>USE MASTER;
  ALTER DATABASE ChurchProject
SET multi_user;
GO</code>

to access the application without using the sql password:

Use
username: reuben
password: haley

<strong>NOTE: do not choose Admin/Finance when using this credentials</strong>
