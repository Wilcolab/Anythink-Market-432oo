# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

First install [Docker](https://docs.docker.com/get-docker/) and start your Docker application so it is running in the background. 

Next, clone the repo and navigate into the root folder:

```sh
$ git clone your-link-from-github
$ cd your-link-from-github
```
Next, run docker-compose to create your image file and container. 

```sh
$ docker-compose up
```

If all goes well and no errors come up, navigate to http://localhost:3000/api/ping and a fun message should appear. 

You are all setup!
