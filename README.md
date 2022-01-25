### What it does
This repo contain cfn templates for deploying CloudFormation using aws codepipeline.
In the simple folder, the cfn template create a custom webserver with sg and website. To run, simple upload the yaml to cloudformation. 

### What i learned
- AWS CodePipeline
- AWS CloudFormation
- IAM
- EC2 & Security group

### How to Run?
- Create our own service roles for awscodepipeline (you can't create as trusted entity so you have to edit ec2 service role for it) with custom inline-policy and trust-relationship provided.
- Create another service role for cloudformation to assume with s3fullaccess policy.
- Create a pipeline.
