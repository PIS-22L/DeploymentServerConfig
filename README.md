# Running app on production server

## Requirements
- Docker


## Prerequisites

- Download backend app (.jar) image from nexus

        curl -L <artifact_url> --output backend.jar

- put downloaded jar file into `backend` directory

        mv ./backend.jar ./backend/backend.jar  

- download built React directory

- put downloaded `build` (React app) to `frontend` directory

- start docker daemon (if not already running)


## Run app

    docker-compose up -d


## Stop app

    docker-compose down