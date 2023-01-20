# docker-project
Deploying a static website on AWS with Docker, Amazon ECR and Amazon ECS

1. Created a Dockerfile in VS Code and build the Container Image.
2. Started the Container and created a repository in Docker Hub and pushed the Image 
3. Created an Amazon ECR Repository to store the image and push the image to the repository

# Project Architecture

1. VPC with public and private subnets in 2 availability zones for high availability.
2. Nat Gateway, Bastion Host and the Application Load Balancer are in the Public Subnets.
3. Security Groups
4. Application Load Balancer for distributing web traffic to the containers.
5. ECS Cluster
6. Task Definition and created Service.
7. Route 53 to register the Domain name and create a record set
8. AWS Certificate Manager to secure web communication to the website.

http://dev-alb-315606208.us-west-2.elb.amazonaws.com/











