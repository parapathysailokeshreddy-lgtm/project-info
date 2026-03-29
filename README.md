# project-info

:

🚀 Sample Python App with GitLab CI/CD Pipeline
📌 Overview

This repository contains a sample Python application (pyapp) integrated with a GitLab CI/CD pipeline that demonstrates automated build and deployment processes.

The goal of this project is to showcase a working implementation of:

Application build automation
Docker image creation
CI/CD pipeline setup using GitLab
⚙️ CI/CD Pipeline Details
✅ Build Pipeline

pipeline is created <img width="1241" height="252" alt="image" src="https://github.com/user-attachments/assets/2159592d-20d0-4086-830d-f5f34f1353b5" />

tests passed test report 
<img width="1398" height="606" alt="image" src="https://github.com/user-attachments/assets/6cc2bfcf-f620-4a29-9ae7-1d3f97834651" />

docker image pushed to gitlab container registery 
<img width="1237" height="597" alt="image" src="https://github.com/user-attachments/assets/b45f6a6a-0ac5-4833-9369-d910d04479ae" />

build artifacts



The build pipeline is fully functional and includes:

Code validation and test execution
Application build process
Docker image creation

All stages in the build pipeline are successfully tested and working as expected.

⚠️ Deploy Pipeline

The deployment pipeline is partially implemented.

Due to time constraints (3 days) and parallel involvement in production deployment work at my organization, the deployment stage could not be fully validated.

However:

The deployment logic and configurations are in place
The pipeline is expected to work once valid Azure credentials and environment setup are provided
🔐 GitLab Access Details

To review the pipeline and configurations:

Username: parapathysailokeshreddy@gmail.com
Password: Wu7NrvjK@d.3i9h
Project link 
infra : https://gitlab.com/sailokeshproject/infra
app code : https://gitlab.com/sailokeshproject/pyapp
app pipelines : https://gitlab.com/sailokeshproject/pyapp/-/pipelines
MR apprepo: https://gitlab.com/sailokeshproject/pyapp/-/merge_requests/1

please provide the email i can provide the access

Azure Integration

The deployment pipeline is designed to work with Microsoft Azure services.

To enable deployment:

we need Provide valid Azure credentials to test the infra and deployment changes
Configure required resources (e.g., Container Registry, Container Apps / App Service)
Update pipeline variables accordingly
