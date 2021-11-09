# Deploy Keycloak to Heroku

This repository deploys the [Keycloak](https://www.keycloak.org) Identity and Access Manangement Solution 
to Heroku.  It is based of Keycloak's official docker image with some slight modifications to use the
Heroku variable for `PORT` and `DATABASE_URL` properly.

FORKED to allow running on a HOBBY DYNO for testing
The deployment will be made with a single Hobby dyno with a free Postgres database attached.

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://heroku.com/deploy?template=https://github.com/heroku/node-js-getting-started/tree/main/tree/master)

