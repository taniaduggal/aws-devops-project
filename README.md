#CI/CD for AWS DevOps with AWS CodeCommit and CodeBuild

For the time being, I've established Continuous integration; next, I'll create Continuous deployment, resulting in CI/CD with CodePipeline and AWS.

The code was at CodeCommit, and from there it went to CodeBuild, where it was built, and then the Artifact of the CodeBuild was stored at AWS S3. Once the code is stored, it can be deployed, which is where CodeDeploy comes in.

Try out this project; it will provide you with hands-on experience with CI/CD in an AWS DevOps process.
