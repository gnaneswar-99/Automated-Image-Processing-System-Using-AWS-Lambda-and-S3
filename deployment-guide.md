# Deployment Guide for Automated Image Processing

## Prerequisites
- AWS Account
- IAM Role with S3 and Lambda permissions

## Steps
1. Create two S3 buckets: input and output.
2. Create IAM Role with:
   - AmazonS3FullAccess
   - AWSLambdaBasicExecutionRole
3. Create Lambda Function:
   - Python 3.9
   - Upload the lambda/image_processor.py code
   - Add Environment Variable: OUTPUT_BUCKET
4. Add S3 trigger:
   - Input bucket
   - Event type: Object Created (PUT)
5. Test by uploading an image to input bucket.
