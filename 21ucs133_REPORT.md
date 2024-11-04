# Assignment Solution Report

This repository seems to aim to create a containerized Flask application and uses an NGINX container as a reverse proxy service for our Flask Application. This would be useful in load balancing in case of multiple serving applications.

---

## Problems & Solutions

### 1. Syntax Issues in Docker-Compose.yaml
There were multiple syntax issues in Docker-Compose.yaml file which were fixed. They're documented in the respective file.

### 2. Syntax Issues in Python Application Dockerfile
While building docker image for the local python app, syntax issues were encountered and their resolutions are commented in the respective file.

### 3. Syntax Issues with NGINX Config and DockerFile and Missing HTML File.
Index.HTML file as mentioned in Dockerfile was missing so it was created and syntax issues in both nginx.conf and dockerfile were fixed. This led to successfull build of docker image for the NGINX container.

### 4. Incorrect MAC Address [Application Bug]
Once the application was deployed, it showed incorrect MAC Address consisting of all Zeros.

---

Screenshots are provided in Screenshots folder!