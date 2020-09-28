Copy the folder "Data" to Disk C
the read format should be like "C:\\Data"

to allow backup and restore database.

if restoring backup fails, execute  this query in sql window using MASTER
----setting database to single user mode after backup error

alter database ChurchProject
set multi_user;
go

to access the application without using the sql password:

Use
username: reuben
password: haley

NOTE: do not choose Admin when using this credentials