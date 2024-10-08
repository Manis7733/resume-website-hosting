# Resume Website with Nginx

This project sets up a simple web server using Nginx to serve a personal resume page. The website is hosted using Docker and Docker Compose.

## Project Structure

- `docker-compose.yml`: Defines the Docker service for the Nginx web server.
- `D:\Projects\Resume Website\resume.html`: The HTML file that contains the resume to be served by the Nginx server.

## Prerequisites

- Docker installed on your machine
- Docker Compose installed on your machine

## Setup

1. **Clone or Download the Project**

   Ensure you have your `resume.html` file saved at the following location:
   D:\Projects\Resume Website\resume.html


2. **Running the Project**

Navigate to the directory containing your `docker-compose.yml` file.

```sh
cd path/to/your/docker-compose.yml
docker-compose up -d --force-recreate
