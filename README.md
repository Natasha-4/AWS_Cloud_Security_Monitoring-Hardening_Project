# AWS_Cloud_Security_Monitoring-Hardening_Project
(AWS EC2 security hardening and monitoring project using CloudWatch and SNS for real-time alerting.)

Overview
This project demonstrates how to deploy, secure, and monitor a virtual machine using Amazon Web Services (AWS). The goal was to configure a secure EC2 instance and set up monitoring with automated alerts.

Project Setup:
-Launched an EC2 instance using Ubuntu Linux
-Configured Security Groups to restrict SSH access to my IP address
-Reviewed SSH settings for secure access
-Set up CloudWatch to monitor CPU utilization
-Created an alarm for CPU usage greater than 80% for 5 minutes
-Configured SNS to send email notifications when the alarm is triggered

Services Used:
-Amazon EC2
-Amazon CloudWatch
-Amazon SNS
-Security Groups
-Linux (Ubuntu)

Outcome: 
The EC2 instance was successfully secured and monitored.
The CloudWatch alarm tracks CPU usage and sends an email alert if usage exceeds the defined threshold.

Te EC2 instance was successfully secured and monitored.
The CloudWatch alarm tracks CPU usage and sends an email alert if usage exceeds the defined threshold.
