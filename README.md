# Serverless-Datalake-Pipeline 🚀

![Project Architecture](./serverless%20datalake.drawio.png)

## Overview
Serverless Watchtower is a solution that monitors, processes, and sends alerts for events in an AWS setup. It uses AWS Lambda, Amazon S3, CloudWatch, and Gmail to provide real-time insights and notifications. This ensures smooth automation and issue tracking.

## Key Features
Serverless Design: Built with AWS Lambda and Amazon S3 for a fully serverless setup.
Real-Time Monitoring: Tracks events using CloudWatch and responds quickly.
Automatic Alerts: Sends email notifications via Gmail for important events.
Event-Driven Workflows: Processes changes in S3 buckets with Lambda functions.
Data Validation: Checks and processes data during uploads to ensure quality.

## Workflow

# Data Uploads:
Files uploaded to Amazon S3 trigger a Lambda function to process the data.
The function checks and extracts the data for further use.

# Event Tracking:
CloudWatch monitors events and activates other Lambda functions as needed.
Processed data is stored in another S3 bucket.

# Alerts and Notifications:
CloudWatch tracks errors or specific metrics.
Gmail sends email alerts for critical issues.

## Benefits

# Scalable: 
Automatically adjusts to handle more tasks as needed.

# Cost-Effective: 
Charges only for what you use, saving money during downtime.

# Easy to Manage: 
Uses AWS managed services to reduce workload.

# Quick Alerts: 
Sends immediate notifications to respond faster to problems.

## Tools Used
Amazon S3: To store files and trigger events.
AWS Lambda: To process data and automate workflows.
CloudWatch: To monitor and log events.
Gmail: To send email alerts.
AWS IAM: To control secure access and permissions.

## Future Plans
Add notifications through Slack or SMS.
Improve error handling and add retry options.
Use Amazon Athena to analyze processed data in detail.

## Note: Replace path/to/your/image.png with your project's diagram or image link.

