# 🛠 DevOps & Cloud Engineer Projects Portfolio

This portfolio includes real-world projects demonstrating my expertise in cloud architecture, DevOps automation, disaster recovery, monitoring, and cost optimization.

---

## 1. High Availability Healthcare Cloud Infrastructure (HIPAA-Compliant)

**Overview**  
Designed and deployed a high-availability, HIPAA-compliant infrastructure for a healthcare provider to securely host patient data.

**Architecture**
- Multi-AZ VPC with public/private subnets
- EC2 in Auto Scaling Groups behind ALB
- RDS PostgreSQL Multi-AZ with cross-region backups
- S3 lifecycle + encryption, AWS WAF and Shield

**Tools**: Terraform, GitHub Actions, Secrets Manager, CloudWatch, GuardDuty  
**Outcome**: 99.99% uptime, HIPAA audit passed, RTO under 5 minutes

---

## 2. E-Commerce Microservices Platform on Kubernetes (EKS)

**Overview**  
Migrated a monolithic e-commerce platform to EKS with GitOps to improve scalability and team velocity.

**Architecture**
- Microservices on EKS with namespace isolation
- RDS backend, S3 + CloudFront frontend, Redis caching
- ArgoCD for canary deployments, HPA enabled

**Tools**: GitLab CI, Helm, Kubernetes IRSA  
**Outcome**: 10x traffic scaling, 90% reduction in deployment time

---

## 3. Centralized Logging and Monitoring Platform

**Overview**  
Built an observability stack for 60+ microservices to reduce incident response time and improve reliability.

**Architecture**
- Fluent Bit > Logstash > Elasticsearch
- Prometheus + Grafana for metrics, Alertmanager + PagerDuty for alerts

**Tools**: IAM, KMS, CloudTrail, GuardDuty  
**Outcome**: MTTR cut by 78%, dynamic SLO dashboards implemented

---

## 4. Serverless Data Processing Pipeline

**Overview**  
Created a serverless ETL pipeline for marketing analytics processing 10M+ events/day.

**Pipeline**
- Kinesis ingestion > Lambda processing > S3 storage > Athena transformation
- QuickSight dashboards for visualization

**Tools**: AWS SAM, CloudWatch  
**Outcome**: 60% cost savings vs EC2, sub-second latency

---

## 5. Multi-Region DR Setup for Fintech App

**Overview**  
Designed DR-ready architecture across us-east-1 and us-west-2 for payment systems.

**Infrastructure**
- Aurora Global, Route 53 health checks, S3 CRR
- Terraform modules for dual-region setup

**Outcome**: Zero data loss in DR drills, 100% automation

---

## 6. DevOps Automation Framework for SaaS Product

**Overview**  
Standardized CI/CD and IaC across 10+ teams using shared libraries and reusable modules.

**Tools**
- Jenkins shared libraries, Terraform modules, SonarQube, Trivy
- Slack + GitHub integrations, PR-based staging previews

**Outcome**: 5x faster onboarding, 100% deployment automation

---

## 7. Cost Optimization and Forecasting Platform

**Overview**  
Deployed CUR analytics pipeline for forecasting and tagging-based cost control.

**Solutions**
- Athena + QuickSight dashboards, EventBridge idle resource detection
- Budgets, alerts, and forecasting models

**Outcome**: Saved $20K/month, improved financial planning

---

📄 You can also download the full PDF version of this portfolio [here](./DevOps_Cloud_Engineer_Projects_Portfolio.pdf)
