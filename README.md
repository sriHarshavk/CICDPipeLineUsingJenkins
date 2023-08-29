 # CI/CD pipeline by integrating Jenkins with AWS CodeBuild and AWS CodeDeploy
Jenkins open-source automation server is used to deploy AWS CodeBuild artifacts with AWS CodeDeploy, creating a functioning CI/CD pipeline. When properly implemented, the CI/CD pipeline is triggered by code changes pushed to your GitHub repo, automatically fed into CodeBuild, and then the output is deployed on CodeDeploy.
The functioning pipeline creates a fully managed build service that compiles your source code. It then produces code artifacts that can be used by CodeDeploy to deploy to your production environment automatically.

# Walkthrough
1)Creating resources to build the infrastructure, including the Jenkins server, CodeBuild project, and CodeDeploy application.
2)Accessing and unlocking the Jenkins server.
3)Creating a project and configuring the CodeDeploy Jenkins plugin.
4)Testing the whole CI/CD pipeline.
