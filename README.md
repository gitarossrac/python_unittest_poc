# Python unittest PoC

You can use this repo to enable unit testing in your Python project.
Just copy-paste those few files here to an empty or already existing project.

## Run

You can use docker to install dependencies and run unit tests.
From project root directory run:

```
docker compose -f ./docker-compose.tests.local.yml build
docker compose -f ./docker-compose.tests.local.yml up
```
