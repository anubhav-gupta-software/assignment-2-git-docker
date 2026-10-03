# Git and Docker Starter Application

This repository contains a small Python web application used to practice Git, GitHub, and Docker workflows.

## Application

The application listens on port 8000 and returns a text response when accessed over HTTP.

## Verification

The application can be verified locally through the published host port 8080.
Within Docker networking, the application can be accessed through container port 8000.

## Usage

Build the Docker image:

docker build -t git-docker-app:test .

Run the application:

docker run --name app-test -p 8080:8000 git-docker-app:test

Access the application at:

http://localhost:8080
