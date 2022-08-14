# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
1. First download [Docker](https://docs.docker.com/get-docker/)
2. Validate docker was installed correctly running `docker -v` and `docker-compose -v`
3. Now clone the reop
4. In the repo's root run `docker-compose up`
5. After the docker finishes it's set up check that you have a valid response from both `http://localhost:3000/api/ping` and `http://localhost:3001/register`
6. Create a user
