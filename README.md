# MERN Stack CI/CD Pipeline Project using GitHub Actions Workflows.

This repository demonstrates setting up an end-to-end CI/CD pipeline for a MERN (MongoDB, Express.js, React.js, Node.js) stack application using GitHub-Actions.

## Overview

This project showcases a comprehensive CI/CD pipeline that automates the build and deployment processes for a 3-tier MERN stack application.
I have created a GitHub-Actions Workflow which when triggered builds and pushes docker images to DockerHub with dynamnic version tags using the actions-build-id and deploys the application on an EC2 Instance which acts like a deployment server using a shell script and Docker-Compose.
Github-Actions was much more efficient in terms of speed of execution and compute resource utilization. Github-Actions uses YAML files for its pipeline script which is much more easier to begin with instead of Jenkins groovy scripts.

For detailed information, execution steps and comparison of Jenkins and Github-Actions please refer to my [blog post](https://amaansayyed.hashnode.dev/automating-mern-stack-deployment-with-github-actions-cicd-pipeline) where I provide step-by-step instructions and insights into each stage of the pipeline setup.
