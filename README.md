# Simple DevOps Project
All the working code is stored in "Kubernetes" Folder.
This Repository is a collection of Implementation documents. 

### Purpose:
By following this repository you can able to setup a DevOps CI/CD Pipeline using
- git
- Jenkins
- Maven
- Ansible
- Docker &
- Kubernetes

## CICD 
Their is only one PIPELINE JOB which takes care of everything and leaves the code and environment clean and simple.
CICD works on git-secrets, sast by sonar, dependency check by owasp.
Artifactory is maintained at docker hub.
at the end of the cicd bassline pen-test is done by owasp zap.

the ansinble plays important part in deployment it
1) creates a docker container out of Dockerfile
2) Executes Deployment and Service on k8s cluster.

