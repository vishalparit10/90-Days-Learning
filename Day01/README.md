AWS Devops:
CodeCommit,CodeBuild, CodeDeploy & Code Pipeline

-- create repository by going to codecommit.
- create a IAM user & generate security credentials from HTTPS Git credentials for AWS CodeCommit.
- add all codecommit permissions to this user
- use vscode to clone the repo created on codecommit to locally.
- once cloned, get inside the repo folder and create the index.html file.
- then commit and push the file to master.
- now create build for that we need to create buildspec.yml file and push to codecommit from local
- now create build 
- once successfuly bild created edit to add Artifact, here we need S3 bucker so create one

- now Code Deploy, create application here, 
