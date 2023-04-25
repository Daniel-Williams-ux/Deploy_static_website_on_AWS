# AWS-Deploy_static_website_on_AWS


The cloud is perfect for hosting static websites that only include HTML, CSS, and JavaScript files that require no server-side processing. 
The whole project has two major intentions to implement:

Hosting a static website on S3 and Accessing the cached website pages using CloudFront content delivery network (CDN) service. 
Recall that CloudFront offers low latency and high transfer speeds during website rendering.
Note that Static website hosting essentially requires a public bucket, whereas the CloudFront can work with public and private buckets.

In this project, I will deploy a static website to AWS by performing the following steps:

I will create a public S3 bucket and upload the website files to your bucket.
I will configure the bucket for website hosting and secure it using IAM policies.
I will speed up content delivery using AWS’s content distribution network service, CloudFront.
I will access the website in a browser using the unique CloudFront endpoint.


## Prerequisites :heavy_check_mark:
AWS Account
Ready starter code - Download and unzip this file.


## Topics Covered:
S3 bucket creation
S3 bucket configuration
Website distribution via CloudFront
Access website via web browser


## Dependencies
Cloud Services
Amazon Web Services S3 - Resource hosting and deployments
AWS CloudFront - CDN for SPA
AWS EKS - Backend API
AWS DynamoDB - Persistent Datastore
AWS Cognito - User Authentication
Performance Tracking and DevOps Tools:
AWS CloudWatch - Performance and Health checks
Sentry - Bug Reporting

## Alternates:
TBD
Google Analytics - Usage Reporting
Alternates:
Mixpanel
Travis (CI/CD)


## Frameworks:
Ionic (Javascript) (Frontend)
Node.js (Javascript) (Backend)


## Final website: https://dmivvi7nblvz7.cloudfront.net
