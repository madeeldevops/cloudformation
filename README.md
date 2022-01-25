### What it does
This repo contain cfn templates for deploying aws codepipeline.
In the simple folder, the cfn template create a custom webserver with sg and website. To run, simple upload the yaml to cloudformation. 

### What i learned
- AWS CodePipeline
- AWS CloudFormation
- IAM
- EC2 & Security group

### How to Run?
- Create service roles for awscodepipeline with custom inline policy and trust relationship
- Create another service role for cloudformation for s3fullaccess.
- Create a pipeline.
