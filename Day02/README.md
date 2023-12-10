Pipeline:

1. By using CodeCommit,CodeArtifact, CodeBuild, & CodeDeploy we can create pipeline which will automatically takes the changes made in CodeCommit.
2. Once pipeline successfull we can check the EC2 ip address for application running.


CodeDeploy & Code Pipeline:

- now Code Deploy, create application here and then create deployment group.
- Setup Agent between codeDeploy and EC2 instance (used script: Setting Up AWS CodeDeploy Agent on Ubuntu EC2).
- created appspec.yml file and scripts then push it to remote and build project again.
- created deployment, created new role for EC2 to get S3 access.
- created deployment group and it will start deploying and result in sucess.
