# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

<<<<<<< HEAD
## How to run locally?
1. [Install Docker](https://docs.docker.com/get-docker/)
2. [Install Docker Compose](https://docs.docker.com/compose/install/)
3. Run `docker-compose up`. 
=======
## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

- For setting up local environment please follow the steps :
1. verify docker and docker-compose is installed `docker -v` and `docker-compose -v`
2. run `docker-compose up` from the project root directory. If Docker is working correctly, the backend should be running and able to connect to your local database.
3. test the backend by opening this link `http://localhost:3000/api/ping`
4. to check the frontend open this link `http://localhost:3001/register`
5. If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register
*Just make sure that you run all scripts in the next quests on one of the containers created by `docker-compose up`.  Also, you can use `docker exec` to run commands on a running container*
>>>>>>> ash_branch
