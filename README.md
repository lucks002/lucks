# lucks
# AWS Cloud Solution Architect Learning Journey

## Introduction

This repository documents my AWS Solutions Architect learning journey. During my learning process, I gained hands-on experience with core AWS services and cloud architecture concepts, including IAM, EC2, S3, VPC, RDS, Route 53, ELB, Auto Scaling, Lambda, and CloudWatch.

The purpose of this repository is to organize my study notes, hands-on labs, architecture diagrams, screenshots, and AWS CLI commands in a structured manner. Through practical exercises and real-world scenarios, I developed an understanding of designing secure, scalable, highly available, and cost-effective cloud solutions on AWS.

This repository serves as both a personal knowledge base and a portfolio showcasing my AWS cloud learning experience, hands-on practice, and preparation for AWS Solutions Architect certification and cloud-related roles.

# AWS-Notes

├── README.md

├── EC2.md

├── S3.md

├── VPC.md

├── IAM.md

├── RDS.md

├── Route53.md

├── ELB-AutoScaling.md

├── Lambda.md

├── Cloudwatch.md

├── Architecture-Diagrams/

├── Mini Projects/

└── Projects/

##Learning Objectives

Understand AWS Cloud fundamentals

Learn cloud architecture best practices

Design scalable and highly available solutions

Implement security using IAM

Gain hands-on experience with AWS services

# Security

IAM (Identity and Access Management)

# Compute

EC2 (Elastic Compute Cloud)

# Auto Scaling

Elastic Load Balancer (ELB)
AWS Lambda

# Storage

S3 (Simple Storage Service)
EBS (Elastic Block Store)

# Networking

VPC (Virtual Private Cloud)
Route 53
Security Groups
Network ACLs

# Database

RDS (Relational Database Service)

# Monitoring

CloudWatch

## Hands-On Labs

Launching EC2 Instances

Creating S3 Buckets

Static Website Hosting using S3

Creating Custom VPC

Configuring Route 53

Creating RDS Databases

Setting up Load Balancers

Auto Scaling Configuration

Lambda Function Deployment

CloudWatch Monitoring

## AWS CLI Commands

### IAM

bash

aws iam list-users

aws iam list-groups

aws iam list-roles


### EC2

bash

aws ec2 describe-instances

aws ec2 describe-security-groups

aws ec2 start-instances --instance-ids <instance-id>

aws ec2 stop-instances --instance-ids <instance-id>


### S3

bash

aws s3 ls

aws s3 mb s3://my-bucket

aws s3 cp file.txt s3://my-bucket

aws s3 sync . s3://my-bucket


### VPC

bash

aws ec2 describe-vpcs

aws ec2 describe-subnets

aws ec2 describe-route-tables


### RDS

bash

aws rds describe-db-instances

aws rds describe-db-snapshots


### Route 53

bash

aws route53 list-hosted-zones

aws route53 list-resource-record-sets --hosted-zone-id <zone-id>


### ELB & Auto Scaling

bash

aws elbv2 describe-load-balancers

aws autoscaling describe-auto-scaling-groups


### Lambda

bash

aws lambda list-functions

aws lambda get-function --function-name <function-name>


### CloudWatch

bash

aws cloudwatch describe-alarms

aws logs describe-log-groups


## Skills Gained

Cloud Computing Fundamentals

AWS Infrastructure Management

Networking Concepts

Security Best Practices

High Availability & Scalability

Monitoring & Troubleshooting









