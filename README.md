# Allow Cresta S3 Data Transfer

[![Launch Stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/create/review?stackName=allow-cresta-s3-data-transfer&templateURL=https://cresta-cloudformation-template.s3.amazonaws.com/allow-cresta-s3-data-transfer/aws/main.yaml)

# AWS Resources

This template creates the following AWS resource and policies required by the Cresta AWS Data Access Integration:

- An IAM role for Cresta to assume for data collection from the Source Bucket

- Policy to read from the Source S3 Bucket in your AWS account

- Log into your admin AWS account/role and deploy the CloudFormation Stack with the button above.
  1. Make sure you have switched to the same region as the Source S3 Bucket that you want to share with Cresta
  2. Fill in all the required parameters.
  3. Click Create stack.

- Wait for the stack creation to complete, then, in CloudFormation Stack view, click on Outputs tab. Take a screenshot of the outputs, and provide it to your Cresta Project Manager.
