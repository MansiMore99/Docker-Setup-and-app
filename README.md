# Docker Guide for Beginners 🐳

To complete my project, I had to learn Docker to use pgvector in PostgreSQL, even though I had no prior experience with Docker. 🚀 I researched extensively, watching videos and reading online content. 📚

This repository is dedicated to those struggling with Docker setup and usage. 🐳 Here is a step-by-step guide to help everyone. 👇
________________________________________________________________________________________________________________________________________________________________________

## What is Docker? 🤔
Docker is an open-source platform designed to automate the deployment, scaling, and management of applications.

### Dockerfile: 
A Dockerfile is a text file with instructions to build a Docker image.

* RUN Dockerfile → CREATE DockerImage
* RUN DockerImage → CREATE Container

### Containers: 
A container is an isolated environment to run any code.

________________________________________________________________________________________________________________________________________________________________________

## Step-by-Step Guide 📋

* Create a Dockerfile 📄
* Add instructions in the Dockerfile to create a Docker image 📝
* Run Dockerfile to create DockerImage ▶️
* Run DockerImage to create a container ▶️
* Access the application running in the container 🌐

________________________________________________________________________________________________________________________________________________________________________

## Instructions in Terminal/Command Prompt 💻

1. Create a Directory:
   $ mkdir welcome-to-docker

   
2. Navigate to the Directory:
   $ cd welcome-to-docker

3. Create and Write a Message inside a File
   $ echo "Hello world!" > index.html
(If the file does not exist, it will be created automatically)

4. Show the Content of the File
   $ cat index.html

5. Create a Dockerfile
   $ touch Dockerfile


6. Add the Following Content to the Dockerfile
   $ FROM nginx
     COPY index.html /usr/share/nginx/html

7. Build the Docker Image
   $  docker build -t welcome-to-docker .

8. Run the Docker Container on Port 8080
   $ docker run -p 8080:80 welcome-to-docker

#### Now, you can access the application running in the container by navigating to http://localhost:8080 in your web browser. 🌐

________________________________________________________________________________________________________________________________________________________________________


This guide covers the basic fundamentals of Docker. I will provide detailed information on other parts like Docker Compose, extensions, and more in the respective folders. 📂





<a href="https://www.linkedin.com/in/mansi-more-0943/"> ![LinkedIn Profile](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white) </a>




