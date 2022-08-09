# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

We don't support forked repositories yet, so first clone the repository using git clone command in git bash. Make sure you have Docker Desktop installed to run the repository.
You can install Docker Desktop ([here](https://docs.docker.com/get-docker/))
You can verify docker is ready by running the following commands in your terminal: docker -v and docker-compose -v.
Once you have done that, head to the terminal and move to the project folder by using the docker cd command. 
Then, run docker-compose up from the project root directory to load Anythink's backend and frontend.
If Docker is working correctly, the backend should be running and able to connect to your local database!