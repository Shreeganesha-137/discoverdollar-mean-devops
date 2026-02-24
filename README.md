discoverdollar-mean-devops/

<img width="272" height="367" alt="image" src="https://github.com/user-attachments/assets/10b0fbd8-6636-4a21-9545-56f9da827777" />


# Discover Dollar MEAN-DevOps Deployment

## Overview
This repository contains a complete MEAN stack application deployed with Docker, Docker Compose, and a CI/CD pipeline using Jenkins.

## Folder Structure
- `backend/` - Node.js API server
- `frontend/` - Angular 15 frontend
- `docker-compose.yml` - Defines all services (MongoDB, backend, frontend)
- `Jenkinsfile` - CI/CD pipeline configuration
- `screenshots/` - Screenshots of build, push, deployment, and UI

## Prerequisites
- Docker and Docker Compose installed
- Jenkins setup with Docker access
- DockerHub account

## Setup & Deployment

Clone the repository:
bash
git clone https://github.com/Shreeganesha-137/discoverdollar-mean-devops.git
cd discoverdollar-mean-devops

--------------Access the application---------------
Frontend: http://<server-ip>/
Backend API: http://<server-ip>:8081/

<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/f3768df4-b0df-4b71-a58b-0ab581c4d3ae" />

<img width="1918" height="1078" alt="output" src="https://github.com/user-attachments/assets/67d9650f-bb70-4179-949e-81912463d0b1" />

<img width="1918" height="1078" alt="output2" src="https://github.com/user-attachments/assets/fd4c1bcb-9447-4b5e-999b-07803b384aa4" />

<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/9e5f9ea2-934a-450d-8946-4cee0432a642" />





In this DevOps task, you need to build and deploy a full-stack CRUD application using the MEAN stack (MongoDB, Express, Angular 15, and Node.js). The backend will be developed with Node.js and Express to provide REST APIs, connecting to a MongoDB database. The frontend will be an Angular application utilizing HTTPClient for communication.  

The application will manage a collection of tutorials, where each tutorial includes an ID, title, description, and published status. Users will be able to create, retrieve, update, and delete tutorials. Additionally, a search box will allow users to find tutorials by title.

## Project setup

### Node.js Server

cd backend

npm install

You can update the MongoDB credentials by modifying the `db.config.js` file located in `app/config/`.

Run `node server.js`

### Angular Client

cd frontend

npm install

Run `ng serve --port 8081`

You can modify the `src/app/services/tutorial.service.ts` file to adjust how the frontend interacts with the backend.

Navigate to `http://localhost:8081/`
