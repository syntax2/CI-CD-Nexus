# CI-CD-Nexus
building a pipeline for Vote App to deploy on ECS.


**here is the link to the project**
https://github.com/dockersamples/example-voting-app


The project aims to set up a continuous integration/continuous deployment (CI/CD) pipeline for a voting app that has already been created. The pipeline is designed to detect changes in the code repository and automatically build a new Docker image of the application. The new Docker image is then uploaded to an EKS (Elastic Kubernetes Service) cluster and deployed on ECS (Elastic Container Service) using Jenkins.

The pipeline can be set up in the following steps:

1. Set up Jenkins:
Install and configure Jenkins on a server, and set up the necessary plugins for building and deploying the application.

2. Set up Docker:
Create a Dockerfile to define the Docker image for the application. The Dockerfile should include all the dependencies required by the application.

3. Automate Docker Build:
Use Jenkins to automatically build the Docker image whenever changes are detected in the code repository.

4. Upload Docker Image to EKS:
Use a tool like Skaffold to upload the Docker image to the EKS cluster.

5. Deploy on ECS:
Configure ECS to deploy and manage the Docker containers that run the voting app.

6. Automate Deployment:
Use Jenkins to automatically deploy the new Docker image on ECS whenever it is built. This ensures that the latest version of the application is always running.

By setting up this pipeline, you can ensure that the latest version of the voting app is always available to users. It also saves time and reduces the risk of errors during the build and deployment process.




