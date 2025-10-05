# aws-data-migration-cloudbase
ProjectName:-Cloud Bases Data Warehouse Using AWS Redshift
# Objective of Project
Develop Cloud Data Warehouse solution for client.
# Problem Statement
Client has data on various databases due to that it was challenging for them to manage all data and do analytical operations on it so they want to collect all data at one centralized platform using AWS Redshift Data Warehousing.
# Solution Satement
Here we need to give the ultimate solution that our customer needed, we have to create AWS Redshift cluster which is the Data Warehousing solution given by the AWS

# here are steps that i had
-Check whether Data is ingested in Landing Bucket or not.
-Create glue job to copy files from Landing S3 Bucket and paste it into Final S3 Bucket
-Create IAM role for Amazon Glue and give it full access of S3, Glue
-Run the glue job manually
-Check whether files got copied in Final Bucket or not
-Now we need to do it automatically
-Create Lambda Function to Trigger Glue job
-create separate IAM role for Lambda and give it full access of S3, Glue, Lambda
-pload file in Landing Bucket and check Lambda Job got automatically invoked or not and check glue job got triggered or not.
-Check data got copied in Final Bucket or not.
-Create Redshift Cluster.
-Use Query editor or any SQL Workbench to connect with Redshift Cluster.
-Create Table inside Redshift Cluster.
-Use copy command to copy data from S3 Final Bucket to Redshift table
-Check all data got inserted or not.




