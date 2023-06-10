# website-template

This is a simple template for starting a website. It sets up an Ingres ([traefik](https://traefik.io/traefik/)), an App ([Next 13](https://nextjs.org/)) and a database ([pocketbase](https://pocketbase.io/)).

## Getting started

### Prerequisites

You need to have a later version of docker and docker-compose installed.

### Installation

  - Clone the repository
  - Copy the environment file `cp .env.example .env` and update (at the very least) the `APPLICATION_NAME` variable
  - Run `docker-compose up -d`

### Usage

  - Visit [http://localhost](http://localhost) in your browser to access the website
  - Visit [http://localhost:8081](http://localhost:8081) in your browser to access the traefik dashboard
  - Visit [http://localhost:8080/_/](http://localhost:8080/_/) To  access the pocketbase admin UI. (provided the ports are mapped in the docker-compose.yml file) The API endpoint is located here [http://localhost:8080/api/](http://localhost:8080/api/)

