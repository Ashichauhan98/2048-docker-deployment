\# Dockerized 2048 Game Deployment



A Dockerized deployment of the classic 2048 game using Docker, Nginx, and Docker Compose.



\## Technologies Used



\* Docker

\* Docker Compose

\* Nginx

\* HTML

\* CSS

\* JavaScript



\## Project Structure



```text

2048-docker-deployment/

├── Dockerfile

├── docker-compose.yml

├── .dockerignore

├── index.html

├── js/

├── style/

└── meta/

```



\## Build the Docker Image



```bash

docker build -t 2048-game .

```



\## Run the Container



```bash

docker run -d -p 8080:80 --name 2048-container 2048-game

```



Or using Docker Compose:



```bash

docker compose up -d

```



\## Access the Application



Open:



```text

http://localhost:8080

```



\## Screenshot



!\[2048 Game Running in Docker](screenshot.png)



\## Features



\* Containerized deployment using Docker

\* Lightweight Nginx web server

\* Docker Compose support

\* Portable and reproducible environment



\## Learning Outcomes



\* Docker image creation

\* Container lifecycle management

\* Port mapping

\* Docker Compose

\* Static application deployment using Nginx



\## Credits



Original 2048 game created by Gabriele Cirulli and licensed under the MIT License.



This repository demonstrates Docker containerization and deployment of the application using Docker and Nginx.



