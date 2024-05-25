
# Dockerized MERN Stack Application using Docker Compose

This repository contains a Docker Compose setup for a MERN stack application setup. It simplifies deployment and scaling by orchestrating multiple containers with Docker Compose.

## Prerequisites
Before getting started, ensure you have the following installed:

- Docker
- Node.js and npm (for local development)

MERN application structure

```bash
  my-mern-app/
├── backend/
│   ├── Dockerfile
│   ├── package.json
│   ├── server.js
├── frontend/
│   ├── Dockerfile
│   ├── package.json
│   ├── public/
│   ├── src/
├── docker-compose.yml
```
    
## Getting Started
1. Clone this repository to your local machine.
2. Navigate to the project directory.

### Docker Compose Setup
1. Open a terminal in the project directory.
2. Run `docker-compose up --build` to build the Docker images and start the containers.

### Services
- Backend API: `http://localhost:5000`
- Frontend Client: `http://localhost:3000`

### Additional Notes
- Adjust Dockerfile(s) and docker-compose.yml as needed for production deployment.
- Feel free to customize the environment variables, ports, or other configurations in the docker-compose.yml file.
