# AI-Based-Image-Moderation-System
## Project Overview
This project uses AWS services to automatically analyze uploaded images.

## Architecture
- Amazon S3
- AWS Lambda
- Amazon Rekognition
- Amazon SNS
- Amazon DynamoDB

## Technologies Used
- AWS
- Python

## Features
- Image upload to S3
- Automatic image moderation
- Detection of inappropriate content
- Notification through SNS

## Project Workflow
1. User uploads an image to S3.
2. S3 triggers Lambda.
3. Lambda invokes Rekognition.
4. Rekognition analyzes the image.
5. Results are stored in DynamoDB.
6. SNS sends a notification.

## Author
R Harshavardhan Singh
