AWS DevOps:

1. Followed TWS AZH course to learn AWS Devops- CodeCommit,CodeBuild. 

2. Used CodeCommit to create repository and then using VScode pushed locally created index, buildspec files to repository.

3. Then Using CodeBuild create build, and if it works fine we can use Artifacts for Artifacts upload location, here created S3 bucket.

4. Then retry build to get the artifacts stored to S3.


- create repository by going to codecommit.
- create a IAM user & generate security credentials from HTTPS Git credentials for AWS CodeCommit.
- add all codecommit power permissions to this user
- use vscode to clone the repo created on codecommit to locally.
- once cloned, get inside the repo folder and create the index.html file.
- then commit and push the file to master.
- now create build for that we need to create buildspec.yml file and push to codecommit from local
- now create build 
- once successfuly bild created edit to add Artifact, here we need S3 bucker so create one and updated and retyr build then artifacts will get uplaoded to S3 location. 
