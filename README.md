# Create-an-eCommerce-Analytical-Platform-utilizing-AWS

Ecommerce analytics covers the complete customer journey, from initial discovery to acquisition, conversion, retention, and support. This data can be valuable in understanding shifts in customer behavior and online shopping trends. To facilitate this, we will establish two analytical pipelines: one for Batch processing and another for Real-time data.

The Batch processing pipeline will handle data ingestion, utilizing the Lake House architecture, and then proceed with processing and visualization. AWS Kinesis, AWS Glue, Amazon S3, and QuickSight will be employed to extract meaningful insights from the data.

On the other hand, the Real-time pipeline will be responsible for detecting Distributed Denial of Service (DDoS) and Bot attacks. For this purpose, we will utilize AWS Lambda, DynamoDB, CloudWatch, and AWS SNS to ensure timely and proactive responses to potential threats.<br>

# Batch Processing
The batch processing will involve data ingestion, lakehouse architecture, processing, and visualization using Amazon Kinesis, AWS Glue, Amazon S3, and Amazon QuickSight to draw insights regarding the following:

Unique visitors per day
During a certain time, the users add products to their carts but don’t buy them
Top categories per hour or weekday (i.e., to promote discounts based on trends)
To know which brands need more marketing

# Online/Real-Time Processing
The real-time processing would involve detecting DDoS and bot attacks using AWS Lambda, Amazon DynamoDB, Amazon CloudWatch, and AWS SNS.

This is the first part of the blog series, where we will focus only on the online/real-time processing data pipeline. In the second part of the blog series, we will dive into batch processing.


![alt text](aws-project.png?raw=true)<br>
