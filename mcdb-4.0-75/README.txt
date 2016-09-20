Coordinator: MCDB Team
Project: Maple Community Database
Description: A database compiled from various sources for use by the Maple Story(tm) gaming community.
Version: Rev 4.0
Code Name: DIE XML DIE

:: Instructions ::
To use the MySQL dump in order to add this database to MySQL, you either need to import it if you use a graphical client, or simply open a command prompt [start -> run -> cmd].
If using the command prompt, enter the command:
mysql -u root -p mcdb < mcdb.sql

Please note that if you get command not found errors, you need to add the path to your MySQL binaries into the Windows PATH variable and make certain you are in the directory containing the .sql file.
MySQL gives you an option to do this upon installation.
Replace "mcdb" with the name of the database/schema you wish to use, of course.

:: Notes ::
As this is a community project, feedback is always welcome.
If you know something useful that should be in MCDB, something useless that shouldn't, or a better way of representing something already in the database, Bui would like to hear from you.

Be sure to look at and agree to the licence information that is found in LICENCE.txt before using or redistributing this software.
