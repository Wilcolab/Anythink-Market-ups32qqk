# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Make sure you have [Docker installed](https://docs.docker.com/get-docker/).

Verify that Docker is isntalled with `docker -v` and `docker-compose -v`.

Run `docker-compose up` from the root project directory.

Test the backend by hitting `http://localhost:3000/api/ping`.

Test the frontend and sign up by going to `http://localhost:3001/register`.

You're all set!
