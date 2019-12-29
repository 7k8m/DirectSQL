# Description
[![Build Status](https://github.com/DirectSQL/DirectSQL/workflows/.NET%20Core/badge.svg?branch=master)](https://github.com/DirectSQL/DirectSQL/actions)<br/>
[![Ready on NuGet](https://img.shields.io/nuget/v/DirectSQL.svg?style=flat)](http://NuGet.org/packages/DirectSQL/)

Execute SQL directly !

This .NET Core library is very thin database framework on top of System.Data.
In this library, you can use SQL directly without taking care for lifecycle of connection, transaction and so on.

In many database framework, direct execution of SQL is more or less barriered from orthodox.
This library resolve issues around that.

Now, this library has supporting code for next DBMS
* SQLite
* SQL Server
* PostgreSQL (Npgsql)
* CockroachDB (Npgsql)
* DB2
* MySql
* ODBC connected DBMS

Documentation is [here](https://directsql.github.io/DirectSQL.Document/doc/).

Please try :smile:.

# How to Build
````
 git clone git@github.com:DirectSQL/DirectSQL.git
 cd DirectSQL
 dotnet build
````
