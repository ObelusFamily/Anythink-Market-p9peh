# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

1. Install Docker from https://docs.docker.com/get-docker/
2. Open Docker and agree to the conditions.
3. In a terminal, run the below commands to confirm that Docker has been installed:
    - docker-v (should give a version number)
    - docker-compose -v (should give a version number)
4. Navigate to the main project root folder and run the **docker-compose** up command to start the frontend and backend services.
5. Open up http://localhost:3000/api/ping to confirm that the connection is active.
6. Open up http://localhost:3001/register to confirm that the frontend services are working.
7. Set up an account so that you can access the system.