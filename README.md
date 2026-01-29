# AWS Secure Resume Hosting Project

This project demonstrates how to securely host a resume on AWS S3
using IAM best practices and controlled public access.

## Project Overview
The goal of this project is to design a secure, real-world cloud setup
where a resume is publicly accessible without exposing the entire bucket.

## AWS Services Used
- AWS IAM
- Amazon S3
- AWS CloudWatch (basic understanding)

## Architecture
- Root user access avoided
- IAM user created for daily operations
- S3 bucket with Block Public Access enabled
- Public access granted only via bucket policy for resume object

## Live Resume Link
The resume is hosted securely on AWS S3 and can be accessed using the link below:

🔗 Live Resume URL:
https://kavita-aws-resume.s3.eu-north-1.amazonaws.com/Kavita_Cloud_Cyber_Resume_Pro.pdf)

## Security Measures Implemented
- IAM user instead of root user
- Block Public Access configured
- Bucket policy allowing limited public access
- No sensitive credentials exposed

## Screenshots
All configuration screenshots are available in the screenshots folder:
- IAM user setup
- S3 bucket creation
- Bucket policy configuration
- Live resume access

## Learning Outcomes
- Hands-on experience with AWS IAM and S3
- Understanding of cloud security best practices
- Practical knowledge of hosting public content securely
- Improved cloud documentation skills

## Status
✅ Project completed
