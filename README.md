# code2cloud
Here's an open source project I built for validating Code-to-Cloud.
Step-by-step instructions:
1) In AWS, create an S3 bucket in the same Region that you'll be deploying into (example: us-east-1). Ensure the bucket has a globally unique name.
2) Upload zipped-code/index.zip to the bucket. This is the deployment package.
3) Deploy a CloudFormation Stack using CloudFormation/CloudFormation.yml. Ensure to use the same Region and bucket name from Step 1.
4) Wait for scans to complete and view the Lambda function in Wiz. This should produce the Code-to-Cloud mappings for IaC and Serverless :)

<img width="1612" height="879" alt="Screenshot 2026-10-23 10 49 44" src="https://github.com/user-attachments/assets/75a95e2a-1b26-48e2-bef0-1ee7a1b7eb6c" />
