# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

To get setup the first time, clone the repo to your local machine. If you haven't already, [install Docker] (https://docs.docker.com/get-docker/). From the project root directory, run ```docker-compose up```. Check that the backend is working by pointing your browser to [http://localhost:3000/api/ping] (http://localhost:3000/api/ping). Check that the frontend is working by pointing your browser to [http://localhost:3001/register] ( http://localhost:3001/register).
