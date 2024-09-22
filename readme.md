# **PROJECT NEBULA**

# **Cloud-Based Solution Utilizing AWS Lambda, API Gateway, DynamoDB, ECS & ECR**

## **Project Overview**
This project showcases a cloud-centric architecture using a suite of AWS services for backend logic execution, API management, serverless computing, and secure data storage. The system is designed to efficiently manage user interactions, handle API calls, and process server-side tasks, all while ensuring scalability, security, and seamless deployment.

## **Architecture Overview**
The architecture integrates various AWS components:
- **AWS Lambda**: Executes backend processes and application logic in a serverless computing environment.
- **Amazon API Gateway**: Acts as the intermediary between the client and Lambda functions via HTTP requests.
- **Amazon DynamoDB**: Serves as a scalable and fast NoSQL database for managing user data.
- **Amazon ECS (Elastic Container Service)**: Orchestrates Docker containers, ensuring scalable and distributed applications.
- **Amazon ECR (Elastic Container Registry)**: Stores Docker images for easy deployment on ECS.
- **AWS IAM (Identity and Access Management)**: Manages access control, ensuring only authorized users can interact with APIs and resources.
- **Amazon CloudWatch**: Monitors logs and metrics, providing insights into the application's performance.

## **Key Features**
- **Serverless Execution**: AWS Lambda enables scalable computing without managing servers.
- **API Integration**: API Gateway connects frontend requests with backend Lambda functions.
- **Data Storage**: DynamoDB offers low-latency, high-throughput NoSQL database services.
- **Containerized Deployments**: ECS and ECR facilitate the deployment of containerized applications, ensuring they scale efficiently.

## **Technology Stack**
- **Backend Services**: AWS Lambda, Amazon API Gateway, DynamoDB, ECS, and ECR.
- **Security and Monitoring**: IAM for access control and CloudWatch for monitoring and logging.
- **Containerization**: Docker for containerized application management.

## **Frontend & Backend Technologies**
- **Frontend**: HTML and CSS for the user interface design.
- **Backend**: PHP is used to manage dynamic content, form submissions, session handling, and database interactions.

## **Getting Started**

### **1. Cloning the Repository**
Do the git clone command on this repo.

2. Prerequisites
Ensure you have the following:

An active AWS account.
Docker installed on your local machine.
AWS CLI set up and properly configured.
3. Deploying the Application
Step 1: Push your Docker container to Amazon ECR.
Step 2: Deploy the application using Amazon ECS.
Step 3: Configure API Gateway to link the frontend with backend Lambda functions.
4. Monitoring and Logging
Use AWS CloudWatch to keep track of the performance and logs of your Lambda functions, ECS containers, and other system components. CloudWatch provides insights into system health, allowing for proactive monitoring and troubleshooting.



