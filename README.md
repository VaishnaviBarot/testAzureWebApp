# PHP App Deployment to Azure Web App

## Description

This repository contains a GitHub Actions workflow for building and deploying a PHP application to Azure Web App. Designed for simplicity and efficiency, the workflow automates the process of setting up the PHP environment, managing dependencies with Composer, and deploying the application with seamless integration of Azure services.

### Features
- **Automated Build and Deployment**: The workflow automatically builds the application whenever changes are pushed to the master branch or when manually triggered.
- **PHP Environment Setup**: Utilizes the latest PHP version (8.2) with the ability to manage dependencies via Composer.
- **Azure Integration**: Uses Azure login and deployment actions to securely deploy the application to Azure Web App.
- **Artifact Management**: Packages the application into a zip file for efficient deployment.

### Prerequisites
- Azure account and subscription.
- Azure Web App created to host the PHP application.
- GitHub repository set up to use GitHub Actions.

### Getting Started
1. Clone this repository to your local machine.
2. Set up your Azure credentials as secrets in your GitHub repository.
3. Push changes to the master branch or trigger the workflow manually to deploy your application.

### Usage
After configuring the repository, any changes pushed to the master branch will automatically trigger the deployment process, ensuring your application is always up to date on Azure Web App.

