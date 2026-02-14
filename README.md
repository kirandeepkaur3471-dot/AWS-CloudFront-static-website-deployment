## Project Overview
This project demonstrates how to securely host a static website using Amazon Web Services (AWS).  
The website files are stored in a private Amazon S3 bucket and delivered to users through Amazon CloudFront, ensuring both security and high performance.

Instead of making the storage bucket public, access is controlled through CloudFront — a real-world architecture used in production environments.


## Architecture Used
User → CloudFront (CDN) → Private S3 Bucket

## AWS Services Used

- Amazon S3 — Storage for static website files  
- Amazon CloudFront — Content Delivery Network (CDN)  
- IAM — Access control and permissions  

## Implementation Steps

1. Created an Amazon S3 bucket  
2. Uploaded static website files (HTML, CSS, JS)  
3. Enabled Block Public Access to keep the bucket private  
4. Created a CloudFront distribution  
5. Configured S3 bucket as the origin  
6. Granted CloudFront secure access to the bucket  
7. Deployed the distribution  
8. Accessed the website via CloudFront URL  

## Key Learnings

- Secure static website hosting on AWS  
- Difference between public and private S3 buckets  
- CDN concepts and edge locations  
- AWS service integration  
- Real-world cloud security practices  

## Project Outcome

Successfully delivered a static website securely and globally without exposing the S3 bucket to public access.
