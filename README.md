# Assignment 1: AWS EC2 Automation Script

Description:
This script automates the following tasks:
- Launching a t2.micro EC2 instance using Amazon Linux 2023 AMI
- Waiting for 15 minutes to simulate workload
- Stopping the instance to save cost

How to Run:
1. Make sure AWS CLI is installed and configured with necessary EC2 permissions.
2. Ensure a key pair named 'mykey' is available in the selected region.
3. Open Git Bash or terminal and run the following command:

   bash deploy.sh

Requirements:
- AWS CLI must be configured
- EC2 Key Pair named 'mykey'
- IAM user should have EC2 launch and stop permissions

Security Note:
- The .pem key file is not included in the GitHub repository
- No hardcoded credentials or secrets are used
