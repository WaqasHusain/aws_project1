# aws_project1
Build an event announcement website using S3, Lambda, SNS, API Gateway, IAM.
Briefly below steps need to be performed, and necessary files index.html, styles.css, and events.json are provided here in this repository.

1- Set up frontend hosting with S3
2- Integrate SNS Notifications and Lambda Functions
3- Setup, Test and Deploy the API Gateway
4- Test and Finalize

This project can be completed staying within AWS free tier.

A user will be able to access a static website hosted in S3 bucket, and view and create events lists, also user can subscribe to event notification list. Lambda functions will be handling back end processing.

Services Used are mentioned below:

AWS S3: Host the frontend and store event data in a JSON file.
AWS SNS: Manage email subscriptions and send event notifications.
AWS Lambda: Handle backend logic for creating events and managing subscriptions.
AWS API Gateway: Provide endpoints for frontend to communicate with backend services.
IAM Roles & Policies: Secure access to AWS resources like S3 and SNS.
