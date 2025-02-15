# Serverless REST API with AWS Lambda & DynamoDB

This project demonstrates how to build and deploy a **serverless REST API** using **AWS Lambda** and **DynamoDB**. The application eliminates the need for traditional server infrastructure, leveraging AWS services for a cost-effective, scalable, and highly available solution.

## Project Overview

This project provides an API that:

- **Handles HTTP requests** using AWS API Gateway.
- **Processes logic** with AWS Lambda functions.
- **Stores data** in **DynamoDB**, AWS's fully managed NoSQL database.

The application showcases serverless best practices, including automatic scaling, simplified deployment, and event-driven architecture.

## Technologies Used

- **Backend**: AWS Lambda (Node.js or Python)
- **API Gateway**: AWS API Gateway for handling HTTP requests and routing them to Lambda functions
- **Database**: DynamoDB (AWS’s NoSQL database for fast and flexible data storage)
- **Authentication**: AWS Cognito for user authentication (optional)
- **Infrastructure as Code (IaC)**: AWS SAM (Serverless Application Model) or AWS CloudFormation for provisioning resources
- **Deployment**: AWS Lambda and API Gateway via AWS SAM CLI or AWS Console
- **CI/CD**: GitHub Actions (optional for automatic deployment)

## Features

- **Serverless Architecture**: The API is built entirely with serverless technologies, avoiding the need for server provisioning and maintenance.
- **Automatic Scaling**: AWS Lambda automatically scales based on traffic, making it cost-effective and efficient.
- **Database**: Stores and retrieves data from DynamoDB, supporting low-latency reads and writes.
- **Secure**: Optional user authentication with AWS Cognito to manage users and protect endpoints.
- **Easy Deployment**: Deploy the application using AWS SAM or CloudFormation for infrastructure management.

## Prerequisites

Before getting started, ensure you have the following:

- An **AWS account** to provision Lambda, API Gateway, and DynamoDB.
- **AWS CLI** installed and configured on your machine.
- **AWS SAM CLI** installed for local development and deployment.
- **Docker** (if you're running Lambda functions locally with SAM).
- **Node.js** (or Python, depending on your function's language).
- Basic knowledge of **AWS Lambda**, **API Gateway**, and **DynamoDB**.
