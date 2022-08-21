### Week 4
This task is to test your undestanding on creating a CICD pipeline

This task will involve you to create create a CICD pipeline for an application. Your CICD pipeline will deploy into a single environment 


## Instructions
1. Use the application you have created in this repo in [Week 3](README.md)
2. Create a CICD pipeline to deploy your application
3. Implement credentials (username or password) check and ssh key check. If credentials or ssh key is found, the pipeline will fail
4. Implement security vulnerability checks using synk or Trivy. If synk or Trivyis found, the pipeline will fail
5. Implement Unit testing. If unit test fails, the pipeline will fail
6. Implement Static code analysis, if Static code analysis fails then it should fail the pipeline
9. Once all gates passes publish your artefacts to a Nexus Registry
10. Deploy your artefacts to a server and share your URL