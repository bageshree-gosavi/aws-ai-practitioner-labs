# Day 1 - Development Environment Setup

## Git & GitHub
- Created GitHub repository
- Learned Git workflow (status, add, commit, push)
- Organized project structure for AWS AI labs

## AWS Account Setup
- Created a new AWS account
- Enabled MFA for the root user
- Created an IAM administrator user
- Learned why IAM users are preferred over the root user
- Created and rotated AWS access keys

## AWS CLI
- Installed AWS CLI v2
- Configured AWS CLI
- Verified authentication using:
  aws sts get-caller-identity

## Cost Management
- Created a monthly $5 AWS Budget
- Configured email alerts for budget thresholds

## Key Commands Learned

```bash
git status
git add .
git commit -m "message"
git push origin main

aws configure
aws sts get-caller-identity
```