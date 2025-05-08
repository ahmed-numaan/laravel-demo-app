# Getting Started with Laravel Demo App

This project was bootstrapped with [Laravel repository on GitHub](https://github.com/laravel/laravel).

## Available Scripts

### 1 . Start container:

docker run -dp 8000:80 --name laravel-demo-app-container anumaan/laravel-demo-app-image

### 2. List running containers:

Open [http://localhost:8000/](http://localhost:8000/) in browser to see running app.

### 3. List running containers:

docker ps

Copy ID of running container.

### 4. Stop container instance:

docker stop [container_id]

### 5. Delete container locally:

docker container rm anumaan/laravel-demo-app-image

### 6. Delete image locally:

docker image rm anumaan/laravel-demo-app-image



