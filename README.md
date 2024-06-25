# 2048 Game Deployment with AWS EKS

This README provides a quick guide for deploying the 2048 game application using AWS Elastic Kubernetes Service (EKS) and Virtual Private Cloud (VPC).

## Prerequisites

- AWS CLI
- kubectl
- eksctl
- Helm

## Steps

1. **Create EKS Cluster:** Set up an EKS cluster with Fargate support.
2. **Create Fargate Profile:** Create a Fargate profile for the `game-2048` namespace.
3. **Deploy the 2048 Application:** Apply the deployment YAML to create the namespace, deployment, service, and ingress resources.
4. **Associate IAM OIDC Provider:** Set up IAM roles and policies required for the AWS Load Balancer Controller.
5. **Install ALB Ingress Controller:** Use Helm to install the AWS ALB Ingress Controller.
6. **Verify Deployment:** Ensure that the ALB Ingress Controller and the 2048 application are deployed successfully.
7. **Access the Application:** Retrieve the external endpoint to access the 2048 game.

For detailed description and execution of the project, refer: https://nishankkoul.hashnode.dev/deploying-a-2048-game-app-with-aws-eks


