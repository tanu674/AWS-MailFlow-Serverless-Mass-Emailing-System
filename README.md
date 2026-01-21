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
  
   <img width="1440" height="900" alt="Screenshot 2026-01-21 at 8 37 28 PM" src="https://github.com/user-attachments/assets/c83e243e-a323-4079-b9f7-5fbfa6b48229" />

5. Lambda reads CSV and sends emails via SES

<img width="1440" height="900" alt="Screenshot 2026-01-21 at 8 49 56 PM" src="https://github.com/user-attachments/assets/e4193027-b8d1-4e53-b6a7-a2468bc088a6" />
<img width="1440" height="900" alt="Screenshot 2026-01-21 at 8 33 09 PM" src="https://github.com/user-attachments/assets/74badffa-21a5-412a-95a6-1aa546e09d42" />






   


