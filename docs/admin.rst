Administrators
==============

System requirements
#########################

- Any web server with mod_rewrite enabled
- PHP 5.6.x with XSL extension
- PostgreSQL >= 9.2
- Composer (https://getcomposer.org/) - for installaton some components.

Installation
############

1. Download the code from github and put to any directory at your web.
2. Run `composer install` at this directory. (It will install Nette and other PHP components.)
3. Create the database at your PostgreSQL database console or client tool.
4. Create here the PostGIS extension (e.g. `CREATE EXTENSION postgis;` if not automatically created)
5. Run SQL scripts located in install directory at PostgreSQL console or admin tool in numerical order (1 - 5).
6. For creating fulltext search indexes in your language edit the install/fulltext.sql script and run it. (English is supported by default)
7. Rename `app/config/local.neon.dist` to `app/config/local.neon` and edit it for access to your database, your contact information etc.
8. Make the directories `log` and `temp` writable for the web server

Updates
#######
In new versions the database structure may sometimes change. In mostly cases the data remains unchanged but update scripts should be run to change some tables. Update scripts are named **u&lt;update-date&gt;_&lt;table-name&gt;.sql**

*Note: If updating, please delete all files under php/temp/cache directory.*

User access
############

During installation these default users are created automatically:
- admin (password = admin)
- editor (password = editor)
- reader (password = reader)

After installation you should login as admin and change the passwords and/or names on Administration / Rights management page.



