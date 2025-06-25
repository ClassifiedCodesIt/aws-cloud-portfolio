# IAM + Policy Simulator Lab

## Objective
Create a secure IAM user with S3 read-only access and verify denied actions using the IAM Policy Simulator.

## Services Used
- AWS IAM
- IAM Groups & Policies
- IAM Policy Simulator

## Key Steps
- Created IAM group `readonly-s3-group` with `AmazonS3ReadOnlyAccess` policy
- Created IAM user `readonly-s3-user` and assigned it to the group
- Verified permissions using Policy Simulator (`s3:PutObject` was correctly denied)
- Inspected attached policy in JSON view

## Screenshots
- iam-user-summary.png (User summary view with redacted ARN)

## Notes
- AWS account ID and ARN were redacted for security
- This lab was completed using the AWS Console only (no CLI)
- All services used are within the Free Tier

