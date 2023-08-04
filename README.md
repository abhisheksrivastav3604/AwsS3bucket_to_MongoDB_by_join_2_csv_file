# How to fetch two CSV files from AWS S3 bucket, join their records, aggregate with QueryRecord, and load into MongoDB

## Aim

The aim is to fetch two CSV files from the AWS S3 bucket, join the records of the two CSV files, aggregate the records using the QueryRecord processor, and load them into MongoDB.

## References

Link: `https://medium.com/@evanescence1106/fetch-object-from-s3-using-apache-nifi-660c314e96b1`

## Prerequisites

To run this project, you need the following prerequisites:

Apache NiFi: You need Apache NiFi installed on your system. If you don't have it, you can follow the instructions on `https://nifi.apache.org/docs/nifi-docs/html/getting-started.html#downloading-and-installing-nifi` to install it.

User and Password: You need a user and password to login to Apache NiFi.

We need the Access Key ID, Secret Access Key, and Bucket Name of AWS.

MongoDB: You need MongoDB installed on your system. If you don't have it, you can follow the instructions on `https://www.geeksforgeeks.org/how-to-install-mongodb-on-windows/` to install it.


## How to Run

To run the project:
Draw The process Flow or import template into Apache NiFi and, 
Click the "Run" button in Apache NiFi to execute the flow.

