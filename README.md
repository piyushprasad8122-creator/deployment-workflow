GitHub Pages Deployment using GitHub Actions

This repository demonstrates a complete CI/CD pipeline that automatically deploys a static website to GitHub Pages using GitHub Actions. Any change pushed to the main branch is validated and deployed without manual intervention.

Live Site:
https://piyushprasad8122-creator.github.io/deployment-workflow/

Project Overview

The goal of this project is to understand and implement continuous integration and continuous deployment for a static website. The deployment process is fully automated using GitHub Actions and GitHub Pages.

When code is pushed to the repository, a workflow is triggered that prepares the site and publishes it to GitHub Pages.

How the Deployment Works

A developer pushes changes to the main branch

GitHub Actions workflow is triggered automatically

The workflow checks out the repository code

GitHub Pages environment is configured

Website files are packaged as an artifact

The artifact is deployed to GitHub Pages

The live site is updated within seconds

This ensures fast, reliable, and repeatable deployments.

Technologies Used

GitHub Actions for CI/CD automation
GitHub Pages for static site hosting
HTML and CSS for the website
Linux (Ubuntu runner) for the workflow execution

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

The workflow is triggered on every push to the main branch.
It uses official GitHub Actions to configure Pages, upload artifacts, and deploy the site.

Key features of the workflow:

Automatic trigger on code push

Least-privilege permissions

Artifact-based deployment

No manual deployment steps

CI/CD Concepts Demonstrated

Continuous Integration through automatic workflow triggers
Continuous Deployment to GitHub Pages
Artifact creation and deployment
Infrastructure-free hosting
Version-controlled deployments

How to Verify Deployment

Push any change to index.html

Open the Actions tab to see the workflow run

Wait for the green checkmark indicating success

Refresh the live site URL to see the update

This confirms that the CI/CD pipeline is working correctly.

Use Case

This project is ideal for:

Learning CI/CD fundamentals

Demonstrating GitHub Actions in interviews

Hosting simple static websites

Building a strong DevOps foundation

Author

Piyush
GitHub: https://github.com/piyushprasad8122-creator
