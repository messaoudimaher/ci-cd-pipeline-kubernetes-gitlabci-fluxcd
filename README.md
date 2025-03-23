Implementing a CI/CD Pipeline for Kubernetes Using GitLab CI and FluxCD

This project sets up a CI/CD pipeline to build and deploy the Spring PetClinic Sample Application to a Kubernetes cluster. It can also serve as a template for deploying other applications.

*Structure
    *spring-petclinic/: Folder contains the Spring PetClinic Sample Application project.
        -Dockerfile: Dockerfile with instructions on how to build the application image.
        -compose.yml: Docker compose file used to build application image and run the container.


*Local Development
   Build, run and test the application.
   1️⃣ Using docker run (without Docker Compose)
    docker run -d --spring-petclinic-container spring-petclinic
   2️⃣ Using docker-compose.yml
    docker-compose up -d
    
    You can then access the Petclinic at http://localhost:8008/.