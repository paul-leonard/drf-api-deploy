# drf-api-deploy
Gunicorn is used as a production server.  The site is hosted on Heroku and the postgres SQL database is on elephantSQL.

## Lab Submission Pull Requests
[Lab33: Authentication & Production Server](https://github.com/paul-leonard/drf-api-deploy/pull/1)

## Release Info
**Author**: Paul Leonard
**Version**: 0.9.0

## Overview
A website and database for daily journal entries was created using Django web and REST framework and containerized using Docker.  Permissions are established so that only the authors can modify and delete their own stories.  Gunicorn is used as a production server.  The site is hosted on Heroku and the postgres SQL database is on elephantSQL.

## Architecture
Website, consisting of webpages and a postgresql database, created using the Django web framework with full Create, Read, Update, and Delete (CRUD) capabilities which are accessible through the Django REST Frameworks API. The website is containerized using Docker.  Restricted permissions are established to prevent inadvertent modification and deletion of book instances stored in the database.  JSON Web Tokens (JWT) are planned to be used for authentication when accessing via API.  Gunicorn is used as a production server.  The site is hosted on Heroku and the postgres SQL database is on elephantSQL.

## Change Log
**0.9.0** 12-29-2020 - Initial beta release
**1.0.0** 12-TBD-2020 - Initial release

## Credits and Collaborations
- [creating a template repository on github](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/creating-a-template-repository)
- [a nice template repository](https://github.com/paul-leonard/drf-auth)
