# terraform-jenkins-aws-ecr
This is a project that store, manage, and deploy Docker and Open Container Initiative (OCI) images securely and reliably.
# challenges encounter during the image building
Jenkins was deployed using the infra folder,while the jenkins was equally configured by using the much needed plugins: docker and docker pipeline and aws ecr.
Jenkins was asked to build using the jenkinsfile but failed due to aws access ( we install aws CLI script)
Jenkins again failed to build bcos dockerfile was empty (input dockerfileand update github)
Jenkins failed tobuild again bcos of a missing file- requirements.txt (pip freeze >> requirements.txt and update github)
Jenkins build was successful with docker image built and push to ecr.

![Image](https://github.com/user-attachments/assets/7190ad19-6181-4653-98c6-33b48254470a)

![Image](https://github.com/user-attachments/assets/aaa4f91e-2683-4832-b6fb-87f49be833d7)