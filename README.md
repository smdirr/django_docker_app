# Django project with PostgreSql and Docker

Empty Django project with PostgreSql 

## Requirements

- Docker
- Docker-compose

   
## Installation

   ```bash

    docker-compose build

    docker-compose up -d --build

    docker-compose exec web python manage.py migrate --noinput
   ```

## Configuration

- entrypoint file 

