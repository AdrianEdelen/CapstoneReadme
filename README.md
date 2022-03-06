This readme is best viewed with markdown enabled, 

##Capstone Project - Adrian Edelen - 

####Running the test application
**The script is written using python 3.9.7 64bit**
\_\_main\_\_.py is a simple application that establishes the connection to the db, removes any existing rows in all tables, generates mock data for each table and commits the rows, then gets all of the rows and prints them, it also demonstrates selecting a specific row by id.

The application should work plug and play as long as the db is in the same directory as the script, regardless of the data in the table already. However there is no exception handling for a locked db, or insert violations (uniqueness, etc).

**Make sure you run the application with a terminal to see the output.**


####Opening the DB to view
I am using the application DB Browser for SQLite on ubuntu.
it can be installed vis apt with `sudo apt-get install sqlitebrowser` or building from the [source](https://github.com/sqlitebrowser/sqlitebrowser "source")

windows executable downloads can be found [here](https://sqlitebrowser.org/dl/ "here")

####Notes
The db attached in the zip file has mock data in it currently, but that data is deleted and rebuilt each time the script is ran. 

The script should be OS agnostic since it uses basic python and sqlite, however I do not have a windows computer to properly test it.
