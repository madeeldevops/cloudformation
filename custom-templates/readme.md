### What it does and how
- ec2-sns-with-customRole
Create InstanceProfile and attach to ec2.
The InstanceProfile have rootRole with assumerolepolicy and policy document.
It also create snstopic with custom condition on endpoint and using email protocol in subscription
- fullstack-changeset.yaml
Template for asg, alb and all the good stuff
- webserverwithallcfn.yaml
Create a webserver with userdata, cloudformation:init helper script in metadata to configure ec2 on the go.