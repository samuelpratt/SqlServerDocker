# SQL Server on Docker for dev / mess around purposes

## Database

* Database init based on <https://cardano.github.io/blog/2017/11/15/mssql-docker-container>
* DB Tables are lifted from here: <https://docs.microsoft.com/en-us/ef/core/get-started/aspnetcore/existing-db>

## Start it up

docker-compose up -d

## SQL Client

* For windows you can use SSMS <https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-2017>
* For Max/Linux you can use Azure Data Studio <https://docs.microsoft.com/en-us/sql/azure-data-studio/download?view=sql-server-2017>

## Passwords

Yes, these are checked in. Yes, this is all running on SA, Yes, I know it's not a good idea IRL. No, it doesn't matter in this case, this is for quick knock-around type stuff.

## Set DB Name

This is done in init.sql

## Adding SQL Tables etc

Put your SQL files in /sql/table/