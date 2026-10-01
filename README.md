# CI/CD Pipeline Project

## Project Name

CI/CD Pipeline using GitHub Actions, Tekton and OpenShift

## Project Description

This project demonstrates a complete CI/CD pipeline for a Python application using GitHub Actions, Tekton Pipelines, and OpenShift.

## Project Objectives

- Automate code validation using GitHub Actions
- Perform code linting using flake8
- Run unit tests using nose
- Automate CI/CD tasks using Tekton
- Build and deploy the application on OpenShift
- Verify the deployed application through OpenShift logs

## Technologies Used

- Python
- GitHub
- GitHub Actions
- flake8
- nose
- Tekton Pipelines
- OpenShift
- Buildah

## CI/CD Workflow

The pipeline performs the following stages:

1. Checkout source code
2. Install dependencies
3. Run flake8 linting
4. Run nose unit tests
5. Build the application image
6. Deploy the application to OpenShift
7. Verify the application logs

## Repository Structure

```text
coursera-project/
├── .github/
│   └── workflows/
│       ├── ci.yml
│       └── workflow.yml
├── .tekton/
│   └── tasks.yml
├── src/
├── tests/
└── README.md
