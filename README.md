# docker-example-go

A minimal Go HTTP server containerized with **Docker** and served through **Nginx** as a reverse proxy — a practical example of a production-like containerized Go application.

## Objective

The objective of this project is to demonstrate how to containerize a Go web application using Docker and Docker Compose, with Nginx acting as the entry point and forwarding requests to the Go backend.

## Tech Stack

- Go (net/http)
- Docker & Docker Compose
- Nginx

## Getting Started

```bash
docker-compose up --build
```

The application will be available at `http://localhost`.
