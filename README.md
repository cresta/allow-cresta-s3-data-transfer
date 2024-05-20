# Allow Cresta S3 Data Transfer

[![Launch Stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/create/review?stackName=allow-cresta-s3-data-transfer&templateURL=https://cresta-cloudformation-template.s3.amazonaws.com/allow-cresta-s3-data-transfer/aws/main.yaml)

This template creates the following AWS resource and policies required by the Cresta AWS Data Access Integration:

- An IAM role for Cresta to assume for data access to the source S3 bucket in your AWS account
- Policy to read from (and optionally write to) the source S3 bucket in your AWS account

## Steps to Deploy

1. Log into your admin AWS account/role
2. Make sure you have switched to the same region as the source S3 Bucket that you want to share with Cresta
3. Deploy the CloudFormation Stack with the `Launch Stack` button above
4. Fill in all the required parameters
5. Click Create stack

Wait for the stack creation to complete.
Then, in CloudFormation Stack view, click on Outputs tab. 
Take a screenshot of the outputs, and provide it to your Cresta account manager.
