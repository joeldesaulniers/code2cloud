# code2cloud
Here's an open source project I built for validating Code-to-Cloud.
Step-by-step instructions:
1) In AWS, create an S3 bucket in the same Region that you'll be deploying into (example: us-east-1). Ensure the bucket has a globally unique name.
2) Upload zipped-code/index.zip to the bucket. This is the deployment package.
3) Deploy a CloudFormation Stack using CloudFormation/CloudFormation.yml. Ensure to use the same Region and bucket name from Step 1.
4) Wait for scans to complete and view the Lambda function in Wiz. This should produce the Code-to-Cloud mappings for IaC and Serverless :)

