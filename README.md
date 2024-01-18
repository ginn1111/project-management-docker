# This project setup for docker compose
1. Setup for dev environment with 3 images
- DB: mcr.microsoft.com/azure-sql-edge
- Client: submodule project-management-client
- Server: submodule project-management-server

2. How to start?
- Clone this project.
- Creating a environment file and configuration.
- Run command in production (`docker compose build` to build docker image and `docker compose up -d` to run project)
- Run command in development (`docker compose -f docker-compose.dev.yaml build` and `docker compose -f docker-compose.dev.yaml up -d`)
