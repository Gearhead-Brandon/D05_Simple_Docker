# Simple Docker

An introduction to Docker and developing a simple Docker image for your own server. The Russian version of the task can be found in the repository.

## Contents

1. [Chapter I](#chapter-i)
2. [Chapter II](#chapter-ii)
    1. [nginx](#nginx)
    2. [Docker](#docker)
    3. [Dockle](#dockle)
3. [Chapter III](#chapter-iii)
    1. [Ready-made docker](#part-1-ready-made-docker)
    2. [Operations with container](#part-2-operations-with-container)
    3. [Mini web server](#part-3-mini-web-server)
    4. [Your own docker](#part-4-your-own-docker)
    5. [Dockle](#part-5-dockle)
    6. [Basic Docker Compose](#part-6-basic-docker-compose)

## Chapter I

A story of someone preparing for a job in DevOps while on a sea voyage, contemplating the work with Docker and creating their own server using Docker images, starting with the official **nginx** image.

## Chapter II

### **nginx**

Nginx is a high-performance, open-source web server and reverse proxy server, commonly used for load balancing, HTTP caching, and handling multiple client requests.

### **Docker**

Docker is a platform for developing, deploying, and running applications in containers. Containers isolate an application and its dependencies from the environment, allowing easy portability and resource efficiency.

### **Dockle**

Dockle is a tool for security checking of Docker images to identify vulnerabilities, suggest improvements, and follow security best practices.

### **Docker Compose**

A tool for defining and running multi-container Docker applications. It simplifies working with complex systems, such as microservices, by handling multiple containers simultaneously.

## Chapter III

### Tasks Overview:

1. **Ready-made docker**: Pull the official nginx Docker image, run it, and check container status and configurations.
2. **Operations with container**: Modify the nginx configuration, create a new configuration file, and manage containers with commands like export, stop, and delete.
3. **Mini web server**: Write a simple "Hello World!" server using C and FastCGI, and configure nginx to proxy requests.
4. **Your own docker**: Build a custom Docker image that contains the mini server and nginx, and configure it to run the server on a specific port.
5. **Dockle**: Use Dockle to analyze the security of the Docker image created in Part 4 and fix any issues found.
6. **Basic Docker Compose**: Write a `docker-compose.yml` file to deploy a project with multiple containers, including the nginx proxy server and the mini web server, and test that the system works as expected.

## Instructions

- Create a report in markdown format, following the instructions provided for each task.
- Each task should be described under its own heading.
- Screenshots, configurations, and source files should be included in the repository according to the task requirements.