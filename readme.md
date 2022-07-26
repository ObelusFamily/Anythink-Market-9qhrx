# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

So first thing’s first - install Docker.

https://docs.docker.com/get-docker/

Then, install the Docker Compose plugin:

https://www.howtogeek.com/devops/how-to-upgrade-to-docker-compose-v2/

Navigate to the local project directory, then run the following in the terminal: 

docker-compose up

You should now be connected to the Anythink Market database.

You can confirm the backend linkage by pointing your browser to http://localhost:3000/api/ping

You can confirm the frontend linkage by pointer your browser to http://localhost:3001/register
