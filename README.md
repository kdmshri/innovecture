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
CICD takes care of git screts, sast by sonar, dependency check by owasp dependency checker.
Artifactory is maintained at docker hub.
at the end of the cicd basseline pen test is done by owasp zap.

the ansinble plays important part in deployment it
1) creates a docker container out of image
2) deployes deployment and service on k8s cluster

