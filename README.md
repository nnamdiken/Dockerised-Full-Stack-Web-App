# Full-Stack FastAPI and React Template

Welcome to the Full-Stack FastAPI and React template repository. This repository serves as a demo application for interns, showcasing how to set up and run a full-stack application with a FastAPI backend and a ReactJS frontend using ChakraUI.

Here are the full requirements for completing this project

1. Ensure the application runs locally before writing your Dockerfiles
2. Configure the Frontend and Backend to listen on port 80
3. Obtain a domain name for the project
- run the advanved DNS 
- Create A records for db (subdomain) and proxy (subdomain) pointing to your VM IP
4. Write Dockerfiles to containerize the frontend and backend
5. Write the docker-compose for building all docker images used 
6. Install adminer to enable database manager through its GUI
7. Configure Nginx proxy manager to handle reverse proxying and 
8. Setup SSL certificates on the domain, the db and proxy subdomain
Let's get started

Prerequisites
A virtual machine running Ubuntu (AWS)
Basic Level Understanding of the Linux CLI

## Project Structure

The repository is organized into two main directories:

- **frontend**: Contains the ReactJS application.
- **backend**: Contains the FastAPI application and PostgreSQL database integration.

Each directory has its own README file with detailed instructions specific to that part of the application.

## Getting Started

To get started with this template, please follow the instructions in the respective directories:

- [Frontend README](./frontend/README.md)
- [Backend README](./backend/README.md)

Thanks. Nnamdi Nwosu.

