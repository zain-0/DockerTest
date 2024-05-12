# Hello from Zain
This repository contains a simple static HTML page that says "Hello from Zain" and a Dockerfile to containerize the web page using Nginx.

## How to Clone and Run
### Prerequisites
Docker installed on your machine. You can download and install Docker Desktop from here.

### Clone the Repository
Open your command prompt or terminal.
Run the following command to clone the repository:
~~~
git clone https://github.com/zain-0/DockerTest.git
~~~
### Build and Run the Docker Image
Navigate to the cloned repository directory. 
Build the Docker image using the provided Dockerfile:
~~~
docker build -t hello-zain .
~~~
Run a Docker container based on the built image
~~~
docker run -d -p 8080:80 hello-zain
~~~

### View the Web Page
Once the Docker container is running, you can view the "Hello from Zain" web page by opening a web browser and navigating to http://localhost:8080.
