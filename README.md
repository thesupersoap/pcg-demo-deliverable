# PCG Deliverable Demo
## Showcasing Docker, React, Spring Boot, and MySQL knowledge

This demo uses the following technologies:
- Docker (to contain and deploy the application services)
- Gradle (to build the Spring Boot application)
- Spring Boot (for the backend API)
- JWT (for authentication)
- React (for frontend)
- MySQL (backend data storage solution)

## Features

- CRUD-ready profile creation, viewing, and editing!
- Logging in and storing session data
- Authentication via JWT

## Installation

This requires Docker to run. Don't have Docker? [Get it here](https://docs.docker.com/get-docker/)! The necessary MySQL files to populate the DB are included in this git repository.

```sh
cd pcg-deliverable-demo
docker-compose up -d --build
```
And that's it! By default, the application will run on [localhost:3000](http://localhost:3000/)
