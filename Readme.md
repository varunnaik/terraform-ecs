This Terraform project will spin up a high availability ECS cluster behind a load balancer. Supports zero-downtime deployments.

1. Spin up an Elastic Load Balancer at the Application level
2. Spin up an Autoscaling group for the project
3. Spin up an ECS cluster to handle Docker images of the product to be deployed
4. Package and deploy an app to ECS
5. Spin up an S3 instance for file storage
6. Spin up an RDS instance for the deployed application to use
7. Spin up multiple VPCs for this project
