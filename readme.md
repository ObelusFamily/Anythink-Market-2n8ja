# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Steps needed to install and run this repo on a New Machine
- Clone the repo from the Github Repository. [Github-Link](https://github.com/ObelusFamily/Anythink-Market-2n8ja.git)
- Download the Docker Desktop software [From](https://docs.docker.com/get-docker/) and install the docker desktop software on the computer.
- To check if the docker Software is installed properly in the system, use command `docker -v` and `docker-compose -v`
-  After the software is installed open the Anythink-Market-2n8ja folder cloned from the github in the terminal and run the command `docker-compose up`. This will build the docker containers of anythink-backend, anythink-frontend, and postgres.
- After the build is done open [Link](http://localhost:3000/api/ping)
    - If everything goes right you will see a success message. If you see a page saying there are pending migrations then press the button saying merge migrations and the problem will be solved.
- That's it the repo is not Set to run on your machine.
