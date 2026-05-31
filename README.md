 Jenkins CI/CD Pipeline Project 🚀
A CI/CD pipeline project using Jenkins to automate build and deployment of a web applicatio
Project Overview
This project demonstrates a complete Continuous Integration and Continuous Deployment (CI/CD) workflow using Jenkins — from code commit to automatic deployment. Tech Stack
Tool	Purpose
Jenkins	CI/CD automation server
Git/GitHub	Source code management
HTML	Web application
Shell Scripts	Build and deploy automation
Pipeline Flow
Developer pushes code
GitHub triggers Jenkins (Webhook)
Jenkins pulls latest code
Build & Test stage
Deploy to server
Application live 
Project Structure
jenkins-cicd-pipeline/
Index.html         Web application file
Jenkinsfile        Pipeline as code (if added)
README.md          Project documentation
Jenkins Setup Used
Jenkins installed on Linux (RHEL/CentOS)
GitHub Webhook configured for automatic trigger
Freestyle Project / Pipeline job configured
Build steps using Shell commands
Deployment to target server via SSH
How to Run
Prerequisites:
Jenkins installed and running
Git plugin installed in Jenkins
GitHub repo connected
Steps:
Clone this repository
bash
git clone https://github.com/ashok2078/my-jenkins-project.git
In Jenkins → New Item → Freestyle Project
Source Code Management → Git → add this repo URL
Build Triggers → GitHub hook trigger
Build Steps → Execute Shell → add deploy commands
Save and Build Now 
What I Learned
Setting up Jenkins from scratch on Linux
Connecting GitHub repo to Jenkins
Automating deployment using CI/CD pipeline
Understanding webhook-based auto triggers
Pipeline-as-code using Jenkinsfile
 Author
Ashok Kumar Kori
ashok.ak78@gmail.com
LinkedIn
GitHub
> *Part of my DevOps self-learning journey — building hands-on skills in CI/CD automation.*
