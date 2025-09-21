# Automated Management of AWS IAM API Keys: Rotation, Deactivation, Creation, Deletion, and Notification

<!-- Profile Header -->
<p align="center">
  <img src="https://lucid.app/lucidchart/22c1291d-f782-415d-a7f3-7c34d4241413/edit?viewport_loc=-3454%2C-5041%2C3066%2C1425%2C0_0&invitationId=inv_3cafdd92-5968-4df6-9fb8-29aa54aafe13" width="800" alt="Automated Management of AWS IAM API Keys: Rotation, Deactivation, Creation, Deletion, and Notification" />
</p>  

<hr/>

## **👨‍💻 Project Overview:**

This project focuses on strengthening the security and compliance posture of an AWS environment by deploying an automated, end-to-end solution for managing IAM (Identity and Access Management) access keys. It integrates key AWS services — including Lambda, CloudWatch EventsBridge, Secrets Manager, Amazon SNS (Simple Notification Service) and IAM — to automate key rotation and deactivation, minimizing risk and ensuring alignment with security best practices.

## **🛠 Key Components and Workflow:**

· AWS Lambda: Automates the rotation and lifecycle management of access keys using serverless compute, eliminating manual intervention.

· Amazon EventBridge (formerly CloudWatch Events): Schedules and triggers Lambda functions at defined intervals to ensure timely execution of key rotation tasks.

· AWS Secrets Manager: Securely stores access keys and enables centralized, encrypted secret management, allowing Lambda to retrieve credentials securely.

· Amazon SNS (Simple Notification Service): To send messages (notifications) to subscriber’s email after Creation and Deletion of access keys.

· IAM: Configures roles and permissions to enable secure and controlled key rotation, as well as automated deactivation of unused keys.

## **🌱 Benefits and Outcomes:**

· Improved Security: Automated key management reduces human error and ensures prompt rotation and deactivation of inactive keys, reducing the risk of unauthorized access.

· Compliance-Ready: Maintains adherence to industry standards and internal compliance policies through consistent, auditable key management practices.

· Operational Efficiency: Minimizes manual workload, allowing teams to focus on strategic initiatives instead of repetitive IAM tasks.

## **💡 Full Project:**

This solution delivers a secure, scalable, and automated approach to IAM access key management, covering both rotation and removal. By leveraging native AWS tools and aligning with best practices, it significantly enhances the AWS environment’s security, ensures regulatory compliance, and reduces administrative burden. <br/>
Check out the full project here: https://medium.com/@utamadalington045/automated-management-of-aws-iam-api-keys-rotation-deactivation-creation-deletion-and-1e4335232114
