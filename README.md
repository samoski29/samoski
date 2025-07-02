AWS Serverless Architecture with CloudFront, S3, API Gateway, Lambda, and DynamoDB

![Blank diagram (3)](https://github.com/user-attachments/assets/1f95f60d-38e9-401d-9ef5-78f5d4a13ea2)


Project Overview
This project demonstrates a fully serverless architecture on AWS to deploy a web application. It leverages:

 DynamoDB for data storage
 Lambda functions for handling GET and POST operations
 API Gateway for exposing APIs
 S3 for hosting static files (HTML, JavaScript)
 CloudFront for content delivery
 Route 53 for domain name mapping (optional)

 Architecture Flow
 User interacts with the frontend hosted on S3 and CloudFront.
 API requests are routed through API Gateway.
 API Gateway triggers Lambda functions to insert or retrieve data from DynamoDB.
 Data is stored/retrieved and returned to the frontend.
