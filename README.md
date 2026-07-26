# Hi, I'm Irfan

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://linkedin.com/in/irfanzulkifle)
[![Email](https://img.shields.io/badge/Email-irfan.zlkfle%40gmail.com-red?style=flat&logo=gmail)](mailto:irfan.zlkfle@gmail.com)
[![Location](https://img.shields.io/badge/Location-Kuala%20Lumpur-lightgrey?style=flat&logo=googlemaps)](https://www.google.com/maps/search/?api=1&query=Kuala+Lumpur)

Cloud and network support engineer in Kuala Lumpur. I'm completing the AWS re/Start program and I'm CompTIA Network+ certified. Currently studying for AWS Certified Cloud Practitioner (exam Aug 2026) and CompTIA Cloud+ (exam Sept 2026).

I'm still learning. I try to build real things rather than just follow labs. Most of my work is hands-on AWS, Linux and Python. Lately I've been getting into AI engineering by running my own Hermes agent on a VPS.

## What I'm into

- Cloud operations, infrastructure support and network troubleshooting
- AWS (EC2, S3, IAM, VPC, Systems Manager), Linux and Python automation
- CI/CD to AWS: GitHub Actions, OIDC keyless deploys, Trivy image scanning
- Containers and orchestration: Docker, Kubernetes (Kind/EKS-ready), Helm basics
- Infrastructure as Code: Terraform, CloudFormation, checkov scanning
- Network monitoring and automation: reachability, port and latency checks
- Security: least privilege, security group analysis, CIS-aligned checks
- AI engineering: running a personal Hermes agent on my VPS, LLM workflows and automation

## Projects

- **ecs-fargate-cicd-pipeline** - FastAPI service that ships to AWS ECS Fargate on every push, using GitHub Actions with OIDC and no static AWS keys. Trivy scans the image and checkov scans the Terraform, both in CI.
- **network-health-monitor** - Async Python tool that checks host reachability and TCP ports and stores uptime and latency in SQLite. It sends a webhook alert only when a host changes state. Scheduled with a systemd timer.
- **aws-vpc-ec2-baseline** - Hardened CloudFormation VPC and EC2 baseline. SSM-only access, no open port 22, CI security scanning.
- **cloud-security-posture-analyzer** - Python CLI that audits AWS-style inventories and flags misconfigurations, mapped to CIS AWS Foundations v1.4.0.
- **hermes-agentic-ai-infrastructure** - Autonomous agent infrastructure on a Linux VPS: 45 cron workflows, 9router LLM gateway, full observability stack.
- **k8s-demo-app** - Containerized FastAPI service deployed to Kubernetes via Terraform with a GitHub Actions pipeline (Trivy vulnerability gate, OIDC-ready).

## Certifications

- CompTIA Network+ - Mar 2026
- AWS AI Practitioner Challenge (Udacity, part of Accenture) - Jun 2026
- AWS Certified Cloud Practitioner (CLF-C02) - in progress, exam Aug 2026
- CompTIA Cloud+ (CV0-004) - in progress, exam Sept 2026
- APAC Cybersecurity Fund Training (Trainocate) - Apr 2026
- Microsoft Applied Skills: Developing Agents in Microsoft Foundry - May 2026
- Google IT Support Professional Certificate - Jul 2020

## Find me

- LinkedIn: [linkedin.com/in/irfanzulkifle](https://linkedin.com/in/irfanzulkifle)
- Email: [irfan.zlkfle@gmail.com](mailto:irfan.zlkfle@gmail.com)
- AWS notes: [aws-notes-website.vercel.app](https://aws-notes-website.vercel.app)
- Location: Kuala Lumpur, Malaysia

Open to cloud, infrastructure, AI engineering and junior DevOps roles. Always happy to learn from people who know more than I do.
