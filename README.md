# AWS-MailFlow-Serverless-Mass-Emailing-System
AWS MailFlow – Serverless Mass Emailing System is a fully serverless, event-driven email automation system built using AWS Lambda, S3, and SES. The system allows users to upload a CSV file of email addresses to an S3 bucket, which automatically triggers a Lambda function to send emails to multiple recipients using Amazon SES.


# Serverless Mass Emailing System using AWS

A serverless system that allows uploading a CSV file of email addresses to send bulk emails automatically using **AWS Lambda, S3, and SES**.

---

## 🚀 Project Overview

This project demonstrates a fully **serverless architecture** for mass emailing using AWS services.  
The system is event-driven: uploading a CSV file to S3 triggers a Lambda function that reads the emails and sends messages using Amazon SES.

---

## 🧩 Architecture & AWS Services

- **Amazon SES** – Secure and scalable email delivery  
- **AWS Lambda** – Serverless backend to process email lists  
- **Amazon S3** – Storage for CSV files containing recipient emails  
- **IAM** – Manage permissions securely  

**Flow:**
1. Upload CSV to S3 bucket  
2. S3 triggers Lambda function  
3. Lambda reads CSV and sends emails via SES  


