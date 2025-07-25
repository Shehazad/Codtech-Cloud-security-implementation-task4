# Cloud Security Report - Task 4 (CODTECH Internship)

## Overview
This report summarizes the implementation of IAM policies, secure storage configuration, and encryption on AWS.

## 1. IAM Policy

- Created a custom IAM policy (`iam-policy.json`)
- Permissions: Read-only access to `secure-storage-bucket`
- Applied to IAM user for secure and limited access

## 2. Secure Storage Configuration

- Created S3 bucket: `secure-storage-bucket`
- Configured bucket policy (`s3-bucket-policy.json`) to:
  - Deny all uploads without encryption
  - Enforce server-side encryption (SSE-S3)

## 3. Encryption Setup

- Encryption type: Server-Side Encryption with S3-managed keys (SSE-S3)
- Optionally support AWS KMS for enhanced encryption control
- Configured to reject uploads lacking SSE headers

## Tools Used

- AWS Console & IAM
- AWS S3
- AWS JSON Policy Editor

## Conclusion

Successfully implemented cloud security best practices using IAM, secure storage, and encryption.
