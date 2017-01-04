# AWS-vpc-boilerplate
A CloudFormation template for deploying the most common components of an AWS VPC

- Follows a 'Write Once, Run Anywhere' approach
- Uses the new YAML format
- Uses CFN mappings to create 'parameter groups' that can be selected by environment.  This makes it easier to maintain large amounts of parameters in complex templates, without requiring seperate parameter stores or scripting (do not use for credentials, use encrypted variables in your deployment tool for that)
