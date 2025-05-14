# jenkins-basic-task2
# Simple CI/CD Pipeline using Jenkins
This repository contains a basic Jenkins pipeline (Jenkinsfile) that automates a CI/CD workflow for a sample application. The pipeline includes:
Build step: Simulates building the application (using echo).
Test step: Simulates running tests (using echo).
Deploy step: Simulates deployment with Docker (using echo).

It is designed to demonstrate a simple continuous integration and deployment process using Jenkins and Docker.

# Repository
URL: https://github.com/TejasMore09/jenkins-basic-task2.git
Branch: main

# Jenkins Pipeline
The Jenkinsfile defines a pipeline with three stages, executed on any available Jenkins agent. It uses Docker to simulate a deployment step.

# Pipeline Stages
Build: Outputs a message and simulates a build process using an echo command.
Test: Outputs a message and simulates running tests using an echo command.
Deploy: Outputs a message and simulates deploying a Docker container using an echo command.
Post Actions: Prints success or failure messages and cleans the Jenkins workspace.
