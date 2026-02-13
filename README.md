GitHub Pages Deployment using GitHub Actions

This repository demonstrates a complete CI/CD pipeline that automatically deploys a static website to GitHub Pages using GitHub Actions. Any change pushed to the main branch is validated and deployed without manual intervention.

Live Site:
https://piyushprasad8122-creator.github.io/deployment-workflow/

Project Overview

The goal of this project is to understand and implement continuous integration and continuous deployment (CI/CD) using GitHub Actions. The deployment process is fully automated and requires no manual steps after code is pushed.

This project was completed as part of the following hands-on DevOps task:

Roadmap.sh Project:
https://roadmap.sh/projects/github-actions-deployment-workflow

How the Deployment Works

A developer pushes changes to the main branch

GitHub Actions workflow is triggered automatically

The repository code is checked out on an Ubuntu runner

GitHub Pages environment is configured

Website files are packaged as a deployment artifact

The artifact is deployed to GitHub Pages

The live website is updated automatically

This ensures fast, consistent, and repeatable deployments.

Technologies Used

GitHub Actions for CI/CD automation
GitHub Pages for static website hosting
HTML and CSS for the website
Linux (Ubuntu) for workflow execution

Repository Structure
deployment-workflow/
│
├── .github/
│   └── workflows/
│       └── deploy.yml
│
├── index.html
├── README.md
GitHub Actions Workflow

The workflow is triggered on every push to the main branch and uses official GitHub-maintained actions.

Key characteristics:

Automatic trigger on push

Least-privilege permissions

Artifact-based deployment

No manual deployment steps

Clean and readable workflow logs

CI/CD Concepts Demonstrated

Continuous Integration via automatic workflow triggers
Continuous Deployment to GitHub Pages
Artifact creation and publishing
Infrastructure-free static hosting
Version-controlled deployments
