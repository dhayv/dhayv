# Hi, I’m David 👋
**Cloud/DevOps Engineer/Platform Architect**  
I design and deliver resilient, automated systems across AWS & Azure with Terraform, Kubernetes, Docker, and GitHub Actions—reducing manual ops, hardening security, and accelerating delivery cycles.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-dhayv-blue?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dhayv/)  
[![Blog](https://img.shields.io/badge/Blog-dev.to/dhayv-black?logo=dev.to)](https://dev.to/dhayv)  
![Profile Views](https://komarev.com/ghpvc/?username=dhayv)  

---



## 🌐 Azure Projects  
![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white) 
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) 
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)

### [Azure FastAPI Application Deployment with CI/CD](https://github.com/dhayv/azure-cicd) | [Blog Post](https://dev.to/dhayv/how-to-deploy-a-fastapi-app-to-azure-with-docker-acr-and-github-actions-30bk)  
Containerized FastAPI → ACR → Azure App Service.  
- Automated deployments with GitHub Actions.  
- Secured registry access with Service Principals & GitHub Secrets.  

### [Azure RAG AI Application – GitOps Platform Deployment](https://github.com/dhayv/azure-rag-app)  
**Azure AKS | GitOps | Argo CD | FastAPI | OpenAI | AI Search | Terraform | Helm | Platform Architecture**  
Part of a multi-repo Azure AI Platform integrating **FastAPI**, **Azure OpenAI**, and **Azure AI Search** within a **GitOps-controlled AKS environment**.  
- Built modular **RAG (Retrieval-Augmented Generation)** workload with caching, retries, and guardrails.  
- Managed infrastructure and deployment with **Terraform + Argo CD App-of-Apps** pattern.  
- Configured **Helm chart versioning** and environment overlays (dev/staging/prod).  
- Implemented **AKS cluster governance** with declarative sync rules, secrets management, and namespace isolation.  

---
## 🌩 Multi-Cloud & Resilience Projects
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white)
![CloudFront](https://img.shields.io/badge/CloudFront-8C4FFF?logo=amazonaws&logoColor=white)

### [Hybrid Chatbot Platform – Multi-Cloud AI Architecture](https://github.com/dhayv/hybrid-chatbot-platform)  
**AWS EKS | Azure AKS | Kubernetes | Terraform **  
Co-engineered with [Dennis Teimuno](https://github.com/dteimuno) — a two-engineer, cross-cloud deployment integrating **AWS EKS** and **Azure AKS** under a shared Terraform and Docker pipeline.  
- Implemented **CloudFront multi-origin failover** for cross-cloud high availability (EKS → AKS).  
- Deployed containerized chatbot application across both clusters.  
- Built reproducible **IaC modules** with VPC, IAM/RBAC, and declarative service manifests.  
- Demonstrated **DevSecOps** design: Terraform for infra, `kubectl` for delivery, CloudFront for edg
---

## ☁️ AWS Projects – Kubernetes & Scaling  
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white) 
![Terraform](https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=white) 
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)

### [Secure AWS EKS Deployment in Private VPC](https://github.com/dhayv/aws-kubernetes-deploy) | [Blog Post](https://dev.to/dhayv/managing-kubernetes-in-a-private-aws-vpc-a-secure-and-automated-approach-4n4c)  
Terraform-provisioned EKS in private VPC, no SSH.  
- Restricted endpoints, enforced IAM roles.  
- Deployed containerized FastAPI app with ECR + Kubernetes manifests.  

### [AWS Auto Scaling Infrastructure with Terraform](https://github.com/dhayv/autoscaling-group) | [Blog Post](https://dev.to/dhayv/from-502-to-200-building-a-auto-scaling-infrastructure-with-terraform-26dn)  
Multi-AZ autoscaling group with Nginx + ALB.  
- Scales EC2s by CPU load.  
- Built with Terraform modules + CloudWatch monitoring.  

---

## 🏗 Terraform & IaC Projects  
![Terraform](https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=white) 
![S3](https://img.shields.io/badge/AWS_S3-569A31?logo=amazons3&logoColor=white) 
![CloudFront](https://img.shields.io/badge/CloudFront-8C4FFF?logo=amazonaws&logoColor=white)

### [Serverless Blogsite with Terraform & GitHub Actions](https://github.com/dhayv/blogsite) | [Blog Post](https://dev.to/dhayv/building-a-cloud-native-blog-platform-with-terraform-11km)  
Next.js + Terraform + S3 + CloudFront.  
- OIDC-secured GitHub Actions pipeline.  
- Zero-downtime static deploys + CDN caching.  
- Near-zero hosting cost.  
- Automated CI/CD with GitHub Actions.  

---

## 🔄 CI/CD & Automation  
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white) 
![CodePipeline](https://img.shields.io/badge/AWS_CodePipeline-FF9900?logo=amazonaws&logoColor=white) 
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

### [Kubernetes Deployment Pipeline with GitHub Actions](https://github.com/dhayv/kubectl-blog) | [Blog Post](https://dev.to/dhayv/build-a-secure-cicd-pipeline-for-amazon-eks-using-github-actions-and-aws-oidc-3b0m)  
OIDC-based GitHub Actions → ECR → EKS (AWS Kubernetes).  
- Eliminated static AWS keys.  
- End-to-end FastAPI container deployment.  

### [AWS EC2 CI/CD Pipeline](https://github.com/dhayv/ec2-deploy) | [Blog Post](https://dev.to/dhayv/building-a-cloud-native-blog-platform-with-terraform-11km)  
AWS CodePipeline + CodeBuild + CodeDeploy.  
- Zero-touch GitHub → EC2 delivery.  
- Quick rollbacks with versioned artifacts.  

### [AWS Static Website Deployment Pipeline](https://github.com/dhayv/auto-deploy) | [Blog Post](https://dev.to/dhayv/building-a-cloud-native-blog-platform-with-terraform-11km)  
CodePipeline → S3.  
- Auto-deploy static sites on every commit.  
- Versioning + rollback built in.  

---

## 🌍 Full-Stack Cloud-Native Platforms  
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white) 
![Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?logo=awslambda&logoColor=white) 
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white) 
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)

### [WiseWalletWin – Full-Stack Cloud-Native Platform](https://github.com/dhayv/WiseWalletWin)   
SaaS paycheck forecasting platform.  
- Migrated SQLite → MongoDB Atlas → 99.999% uptime.  
- Refactored monolith into Lambda backend → cut cold starts 70%.  
- CI/CD with GitHub Actions OIDC → reduced deploy time 30m → 5m.  
- Reduced container footprint 60% via multi-stage builds.  

---

## 📊 Monitoring & Tooling  
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white) 
![CloudWatch](https://img.shields.io/badge/AWS_CloudWatch-FF4F8B?logo=amazonaws&logoColor=white)

### [Grafana Monitoring Automation on AWS](https://github.com/dhayv/Grafana-scripts) | [Blog Post](https://dev.to/dhayv/deploying-grafana-on-an-aws-ec2-instance2025-3li8)  
Grafana + CloudWatch dashboards with stress-test visualizations.  
- IAM-based access.  
- CPU, network, disk, and health monitoring.  



---

## 📈 GitHub Stats
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=dhayv&show_icons=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=dhayv&layout=compact)
