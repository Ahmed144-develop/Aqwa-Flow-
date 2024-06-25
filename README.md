Introduction
The Sustainable Water Delivery Web App project aims to create an innovative e-commerce platform for water delivery. This project supports the global mission of ensuring universal access to clean water and sanitation services by introducing sustainable technological solutions. The application provides functionalities for customers to manage their orders and for administrators to efficiently manage products and users, all built on a secure and user-friendly ASP.NET framework integrated with AWS services.

Previous Cloud Architecture Blueprint
The initial architecture utilized AWS Elastic Beanstalk for hosting the ASP.NET web application and Amazon RDS for the database, with a focus on simplicity and managed services.

Brand-New Cloud Architecture Blueprint
The updated architecture deploys the application within a Virtual Private Cloud (VPC) using multiple AWS services including SQS for message queuing and API Gateway for handling API requests, ensuring better scalability and performance.

AWS Implementations
AWS CloudFront and S3 Implementation
S3 Bucket Creation: Set up a bucket for storing application assets.
Bucket Policy Configuration: Define access policies for the bucket.
CloudFront Distribution: Create a distribution to serve content globally with low latency.
AWS Lambda Implementation
Develop Lambda functions for processing incoming messages from SQS and sending notifications via SNS.

AWS API Gateway Implementation
Set up API Gateway to handle HTTP requests and integrate with Lambda functions for processing cart operations.

AWS Simple Queue Services Implementation
Implement SQS for handling order and inventory messages, ensuring decoupled and scalable communication between application components.

AWS Simple Notification Services Implementation
Configure SNS for sending notifications related to order processing and updates.

Performance Analysis
The performance analysis section includes CPU and memory utilization metrics, as well as a service map from AWS X-Ray to visualize application performance and identify bottlenecks.

Conclusion
The project demonstrates significant progress towards achieving SDG 6 by providing a reliable and scalable solution for water delivery. The use of AWS services ensures the application is both robust and efficient.

Future Improvements
Enhance user interface for better user experience.
Implement additional security measures.
Expand functionality to support more regions and languages. 
![Picture3](https://github.com/Ahmed144-develop/project2.net/assets/135183754/02bac0c7-b511-4afe-81b3-449ce84445f8)
![Picture2](https://github.com/Ahmed144-develop/project2.net/assets/135183754/da85984b-7f9c-41bf-aeba-f140d33aca53)
![Picture1](https://github.com/Ahmed144-develop/project2.net/assets/135183754/fb260fec-3cf5-4b61-8569-4fafef893d44)
![Picture4](https://github.com/Ahmed144-develop/project2.net/assets/135183754/514874f9-038c-489b-b9f7-7278fe20e0bf)

