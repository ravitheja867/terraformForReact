# terraformForReact
List of Technologies Used
Amazon ECS — a fully managed container orchestration service
Amazon ECR — a fully-managed Docker container registry
Terraform — an open-source infrastructure as code tool

Pre-requisites
An AWS account
Node installed
Docker installed and some basic hands-on experience

Terraform installed
Overview and Steps To be Followed
I followed the steps as mentioned below in order so that we would be able to replicate the same scenario on your local instance with the complete application deployed on AWS instance:
Git Clone the Weather Application Repository.
Dockerise the React based web application.
Create an image repository on AWS ECR and push the image.
Create an AWS ECS cluster.
Create an AWS ECS task.
Create an AWS ECS service.
Create an elastic load balancer for traffic balancing.