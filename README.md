# PostgreSQL Database - book SQL Practice Problems

This is a PostgreSQL compatible sql file to create the database used in the book **SQL Practice Problems**, written by Silvia Moestl Vasilik.

The books website is [SQLPracticeProblems.com](SQLPracticeProblems.com)

Thanks goes to **Silvia Moestl Vasilik** for permission to post this file.

## Usage

You can make use of this sql file from inside **psql** by using the command **`\i posgres_practice_utf8.sql`** as long as this file is in the current path. This will create a database titled **northwind_spp** with its requisite tables and practice data.

After the creating the database, if you are still inside **psql** you can switch to the new database with the command **`\c northwind_spp`** command (**`\c`** is short for **`\connect`**)

You should then be able to access the new database directly on subsequent uses with the following command (bash version shown):

**`psql -U USERNAME northwind_spp`**



