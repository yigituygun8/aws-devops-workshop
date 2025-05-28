# 28.05.2025 - Amazon University Engagement DevOps Event

## Workshop Objectives

- How to effectively leverage various AWS services to improve developer productivity and reduce time to market for new product capabilities.  
- Incrementally adopt and embrace some of the best practices around continuous integration and delivery using AWS Developer Tools and 3rd party solutions including:  
  - AWS CodeBuild (a fully managed build service)  
  - AWS CodeDeploy (a fully managed continuous delivery service)  
- Best practices and tips that can help make your software release process fast, automated, and reliable.

## Services used in this workshop

- **AWS CodeBuild**: AWS service to build artifacts, given the code in the AWS CodeCommit repository.  
- **AWS CodeDeploy**: AWS service to deploy the application, in this case in an Amazon ECS cluster.  
- **Amazon Elastic Container Registry (ECR)**: Used as a registry to place the generated container images.  
- **Amazon Elastic Container Service (ECS)**: Used to create the containers (tasks) which are running in the cluster (it contains the application being deployed by the pipeline).  
- **GitHub**: Used as the repository of the project and connecting it to AWS services.
