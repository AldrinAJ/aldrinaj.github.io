---
title: DevSecOps Master Program - AWS 1.1
date: 2025-07-02 12:50 +0200
categories: [Cloud computing, AWS, Linux, Network]
tags: [Linux, Cloud computing, AWS, DevOps, DevSecOps]
---

# DevSecOps Master Program - AWS 1.1 

## 1. Cloud Basics
**Learning Objectives:**
- Understand differences between public, private, and hybrid clouds
- Compare cloud vs on-premises solutions
- Cloud service models:
  - **IaaS** (Infrastructure as a Service)
  - **PaaS** (Platform as a Service)
  - **SaaS** (Software as a Service)

## 2. Introduction to AWS
**Learning Objectives:**
- AWS global infrastructure (Regions, AZs, Edge Locations)
- Core AWS services:
  - Compute
  - Storage
  - Database
  - Networking
  - Security
  - Applications

**Hands-on Labs:**
- Create AWS free tier account
- Configure billing alerts
- Set up billing preferences

## 3. Virtual Private Cloud (VPC)
**Learning Objectives:**
- VPC components:
  - Subnets
  - Route Tables
  - Internet Gateway
- CIDR concepts
- VPC peering and endpoints
- NACL vs Security Groups

**Hands-on Labs:**
- Create and configure VPC
- Set up NAT Gateway/NAT instances
- Configure VPC peering

## 4. EC2 (Elastic Compute Cloud)
**Learning Objectives:**
- Instance types (Memory/CPU optimized)
- AMIs (Amazon Machine Images)
- Purchase options:
  - On-demand
  - Reserved
  - Spot
  - Scheduled

**Hands-on Labs:**
- Launch Linux/Windows instances
- Create custom AMIs
- Attach EBS volumes

## 5. Storage Services
**Learning Objectives:**
- S3 storage classes:
  - Standard
  - Standard-IA
  - Intelligent Tiering
  - Glacier/Glacier Deep
- EBS vs EFS vs FSx

**Hands-on Labs:**
- Configure S3 lifecycle policies
- Set up static website hosting
- Attach EFS to instances

## 6. Load Balancing & Auto Scaling
**Learning Objectives:**
- Load Balancer types:
  - Classic
  - Application
  - Network
- Auto Scaling policies

**Hands-on Labs:**
- Configure ALB with target groups
- Set up scaling policies based on CPU

## 7. Route 53
**Learning Objectives:**
- Domain registration
- Routing policies:
  - Weighted
  - Latency
  - Failover
  - Geolocation

**Hands-on Labs:**
- Register a domain
- Configure health checks
- Set up DNS records

## 8. CloudFront
**Learning Objectives:**
- CDN configuration
- Origin groups
- Cache behaviors
- Geo-restrictions

**Hands-on Labs:**
- Create CloudFront distribution
- Configure country blocking
- Cache invalidation

## 9. IAM (Identity & Access Management)
**Learning Objectives:**
- Users/Groups/Roles
- Policy management
- MFA configuration
- Cross-account access

**Hands-on Labs:**
- Create IAM policies
- Set up MFA
- Configure STS

## 10. Database Services
### RDS
- Managed SQL databases:
  - Aurora
  - MySQL
  - PostgreSQL
  - Oracle
- Read replicas

### DynamoDB
- NoSQL features
- Global tables
- Auto-scaling

**Hands-on Labs:**
- Create RDS with Multi-AZ
- Configure DynamoDB streams

## 11. Monitoring
### CloudTrail
- Management events
- Data events
- Insights

### CloudWatch
- Metrics/Alarms
- Logs/Events
- Dashboards

**Hands-on Labs:**
- Set up billing alarms
- Create CloudWatch events

## 12. Application Services
- SNS (Notifications)
- SQS (Queuing)
- SES (Email)

**Hands-on Labs:**
- Configure SNS topics
- Set up SQS queues

## 13. Well-Architected Framework
**Five Pillars:**
1. Operational Excellence
2. Security
3. Reliability
4. Performance Efficiency
5. Cost Optimization
