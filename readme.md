# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
1. At first, install docker on your system from the following link
[Install Docker](https://docs.docker.com/get-docker/)

2. After installation, you can verify whether the docker is working or not by using the following commands.
```bash
    docker -v
    docker-compose -v
```

3. Then run **docker-compose up** on the project root directory to run Anythink's frontend and backend.
```bash
    docker-compose up
```

4. If everything works fine, then the backend server will point to the following links. Just click the link and test it.
[http://localhost:3000/api/ping](http://localhost:3000/api/ping)

5. Now, it's time to check the frontend and make sure it is connected to backend.
[http://localhost:3001/register](http://localhost:3001/register)

6. Great job! Now register here with a cool username.
