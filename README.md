# cloudformation-template
Easily set up Cresta data integration using CloudFormation

# Cresta AWS Data Access Integration

[![Launch Stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/create/review?stackName=cresta&templateURL=https://cresta-cloudformation-template.s3.amazonaws.com/aws/main.yaml)

## Installation
1. Ask your Cresta Account Manager for the External ID and Destination Bucket Name
1. Log into your admin AWS account/role and deploy the CloudFormation Stack with the button above.
   1. Make sure you have switched to the same region as the Source S3 Bucket
   1. Fill in all the `required` parameters.
   1. Click **Create stack**.
1. Take a screenshot of the outputs after template creation is complete, and send to your Cresta Account Manager

## AWS Resources

This template creates the following AWS resource and policies required by the Cresta AWS Data Access Integration:

- An IAM role for Cresta to assume for data collection from the Source Bucket
- Policy to read from the Source S3 Bucket in your AWS account
- Policy to write into the Destination S3 Bucket in account managed by Cresta
