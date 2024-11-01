# Docker-mini-project

This repository contains a mini Docker project developed as part of a school assignment. The project demonstrates foundational skills in containerization using Docker and Docker Compose, focusing on building a microservice-based application.

Project Overview

    This project includes:

    Multi-Container Setup: A web application, database, and Adminer interface, each containerized for easy deployment and isolation.
    Service Networking: Configured with Docker Compose to ensure seamless communication between services on the same network.

Requirements

    Docker
    Docker Compose

Setup and Usage

    Clone the repository:
        git clone https://github.com/Dina-Mechraoui/Docker-mini-project.git
        cd Docker-mini-project
    Start the containers:
        docker-compose up -d
    Access the application:
        127.0.0.1:8090/add
        127.0.0.1:8090/all
        127.0.0.1:8091
    Stop the containers:
        docker-compose down

