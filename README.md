# Bike Stores Sample Database

This sample database has been copied and adapted for SQLite from the original found at

http://www.sqlservertutorial.net/load-sample-database/

## Download

Grab a copy of the SQLite database from the [releases](releases) page.

## Manual Installation

To install the database, execute the following from the command line (you can change `bikestores.sqlite3` to the filename of your choice):

```
> sqlite3 bikestores.sqlite3 < bikestores_structure.sql
> sqlite3 bikestores.sqlite3 < bikestores_data.sql
```
To use the sample database, connect to the database with SQLite:

```
> sqlite3 bikestores.sqlite3
```

## Notes

Dates in the `orders` table have been changed from YYYYMMDD format to YYYY-MM-DD format.