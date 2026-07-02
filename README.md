 **Dockerized 2048 Game Deployment**

This project demonstrates how a simple web application can be packaged and deployed using Docker.

I containerized the classic open-source 2048 game using Docker and Nginx to create a lightweight, portable, and reproducible deployment environment. The application runs inside a Docker container and can be accessed locally through a web browser or deployed to cloud platforms that support Docker containers.

**Live Demo**

The application is deployed publicly and can be accessed through the Render deployment link.
https://two048-docker-deployment.onrender.com/

 **Screenshot**

https://github.com/Ashichauhan98/2048-docker-deployment/blob/main/screenshot.png 

**Tech Stack**

* Docker
* Docker Compose
* Nginx
* HTML
* CSS
* JavaScript
* Git
* GitHub
* Render

**Project Structure**

```text
2048-docker-deployment/
├── Dockerfile
├── docker-compose.yml
├── .dockerignore
├── README.md
├── screenshot.png
├── index.html
├── js/
├── style/
└── meta/
```

**Running the Application Locally**

# Build the Docker image


docker build -t 2048-game .

# Start the container

docker run -d -p 8080:80 --name 2048-container 2048-game


Or use Docker Compose:


docker compose up -d

# Access the application

Open your browser and visit:

http://localhost:8080

**Features**

* Dockerized deployment of a static web application
* Lightweight Nginx web server
* Docker Compose support
* Simple and reproducible deployment process
* Ready for cloud deployment using Docker-compatible platforms

# What I Learned

Through this project I gained practical experience with:

* Creating Docker images using Dockerfiles
* Managing Docker containers
* Port mapping between containers and the host machine
* Serving static content using Nginx
* Using Docker Compose for application management
* Deploying Docker applications to cloud platforms

# Future Improvements

* Add CI/CD using GitHub Actions
* Publish Docker images to Docker Hub
* Deploy using Kubernetes
* Implement automated deployments

## Credits

The original 2048 game was created by Gabriele Cirulli and is distributed under the MIT License.

This repository focuses on demonstrating containerization and deployment practices using Docker and modern DevOps tools.
