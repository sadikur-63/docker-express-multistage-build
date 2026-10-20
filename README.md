# Docker Express Multi-Stage Build

A minimal Express.js application built using Docker multi-stage builds.

## Features
- Multi-stage Docker build to keep image sizes small.
- Node.js Express server listening on port 3000.
- Configured with `.gitignore` and `.dockerignore` to keep dependencies clean.

## Prerequisites
- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- [Node.js](https://nodejs.org/) (optional, for local development)

## Getting Started

### 1. Clone the Repository
```bash
git clone [https://github.com/sadikur-63/docker-express-multistage-build.git](https://github.com/sadikur-63/docker-express-multistage-build.git)
cd docker-express-multistage-build
2.docker build -t express-multistage . (Build the Docker Image)
3.docker run -d -p 3000:3000 --name express-app express-multistage (Run the Container)
3.curl http://localhost:3000 (Test the Application)
4.docker logs express-app (Check Container Logs)
