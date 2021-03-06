This is a small task to assess your skill in hosting web applications.
You'll need to host a small PHP site on a publicly-accessible URL. The
site connects to a PostgreSQL server, which you'll have to provide.

Server Environment
------------------
Please use CentOS for this test. You may fork this repository and push
your work to a new branch. Please save and commit all your configs
into the `config/` folder in the Git repository. You are free to use any
configuration management tool you choose.

PHP Application
---------------
We have provided a simple PHP application that talks to a small PostgreSQL
database. The PHP application is found in `src/`. The PHP application has
dependencies that must be installed with PHP's `composer` package manager.
The PHP application uses environment variables for configuration. See the
file `.env.example` for the variable names that should be set.

Database
--------
A PostgreSQL database dump is in `data/`. Please load this dump into a
PostgreSQL database.

The PHP application uses environment variables to configure the database
connection. see `.env.example` for the connection variables that are used.
You may set the environment values to whatever you need to get up and running.

Web Server
----------
Use any web server you like to serve the PHP application.

Hosting
-------
You may choose whichever hosting provider you like, so long as it runs CentOS.

When finished, please send the SSH credentials to `slice@silverorange.com` so we
may look at the server. Also include a link to the github branch which contains
all your work.

Good luck!

