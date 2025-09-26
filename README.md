# Java Web App Deployment with AWS CI/CD

Welcome to this project combining Java web app development and AWS CI/CD tools!

<br>

## Table of Contents
- [Introduction](#introduction)
- [Technologies](#technologies)
- [Setup](#setup)
- [Contact](#contact)
- [Conclusion](#conclusion)

<br>

## Introduction
This project introduces creating and deploying a Java-based web app using AWS services, especially their CI/CD tools.

The deployment pipeline I'm building around the Java web app in this repository is invisible to the end user but makes a big impact by automating software release processes — improving speed, reliability, and scalability.

<br>

## Technologies
Here’s what I’m using for this project:

- **Amazon EC2**: I'm developing my web app on Amazon EC2 virtual servers, so that software development and deployment happen entirely in the cloud.
- **VS Code**: My IDE of choice is Visual Studio Code. It connects directly to my EC2 instance, making it easy to edit code and manage files remotely.
- **GitHub**: All my web app code is stored and versioned in this GitHub repository.
- **[COMING SOON] AWS CodeArtifact**: Once implemented, CodeArtifact will store my artifacts and dependencies, improving availability and build speed.
- **[COMING SOON] AWS CodeBuild**: CodeBuild will handle the build process, compiling source code, running tests, and producing deployable packages.
- **[COMING SOON] AWS CodeDeploy**: CodeDeploy will automate deployments across EC2 instances.
- **[COMING SOON] AWS CodePipeline**: CodePipeline will automate the entire process from GitHub to CodeDeploy, integrating build, test, and deployment steps into one seamless workflow.

<br>

## Setup
To get this project up and running on your local machine, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/nextwork-web-project.git
    ```
2. Navigate to the project directory:
    ```bash
    cd nextwork-web-project
    ```
3. Install dependencies:
    ```bash
    mvn install
    ```

<br>

## Contact
If you have any questions or comments about the NextWork Web Project, please contact:  
**Samuel Itiola** – [samuelitiola.uk@gmail.com](mailto:samuelitiola.uk@gmail.com)

<br>

## Conclusion
Thank you for exploring this project! I'll continue building this pipeline and applying my learnings to future projects.

A big shoutout to **[NextWork](https://learn.nextwork.org/app)** for their project guide and support.  
[You can get started with this DevOps series project too by clicking here.](https://learn.nextwork.org/projects/aws-devops-vscode?track=high)
