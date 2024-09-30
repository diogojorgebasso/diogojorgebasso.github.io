---
title: "Understanding Docker: A Bootcamp Overview"
date: "2024-09-17 14:23:18 +0200"
categories: ["Docker", "Virtualization"]
tags: ["Docker", "Containers", "Linux", "Virtualization", "DevOps"]
---

Docker is a powerful tool that makes it easier to use containers, especially on Linux. In this bootcamp, we explored how Docker works, how to install it, and the basic commands to manage containers. Here's a quick summary of what we covered:

- **What is Docker?** Docker is a platform that lets you run applications in containers, making it easier to deploy and manage apps. It’s different from virtual machines because it shares the same OS kernel but still isolates your applications.
  
- **Installing Docker**: For Linux, installation is simple with `sudo apt-get install docker`. On Windows, enable WSL2 and install Docker Desktop, and on Mac OS, follow the Docker Desktop installation guide.
  
- **Basic Commands**:
  - `docker run hello-world` – Test if Docker is working.
  - `docker ps` – List running containers.
  - `docker images` – View downloaded images.
  
- **Docker Hub**: Docker Hub is a registry for container images. We learned to pull images like `ubuntu:20.04` from Docker Hub and run containers from them.

- **Creating and Managing Containers**: We learned to create, stop, and delete containers using Docker commands. We also learned to create new images from modified containers and share them using `docker commit` and Docker Hub.

- **Volume Sharing**: You can share files between your computer and a container using Docker volumes, which is helpful when you want to persist data or test with local files.

- **Networking**: Docker also allows containers to communicate over the network. By exposing ports, we can access applications running inside containers, such as an NGINX web server.

- **Dockerfile**: This is a file where you define how to build a custom Docker image. You specify the base image, copy files, run commands, and set up the environment.

- **Best Practices**: 
  - Keep images small and simple.
  - Use one process per container.
  - Avoid running everything as root inside the container for security reasons.

This bootcamp was an excellent introduction to Docker and how containers can make software development and deployment more efficient. Docker is widely used in DevOps, and knowing how to use it can be a valuable skill for anyone in software development.

Sources:
- [Docker Official Site](https://www.docker.com/)
- LORIA Docker Bootcamp materials by Adrien Guenard
