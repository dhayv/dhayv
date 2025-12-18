# David Hyppolite | DevOps Engineer

I make deployments faster, infrastructure cheaper, and systems reliable.

**What that looks like:**

- Deployments compressed from 30 min → 5 min
- Cloud costs cut 40% through architecture optimization
- Release reliability improved 70% with automated pipelines
- Production systems operated through 6 architecture migrations

**Stack:** AWS · Azure · Terraform · Kubernetes · ArgoCD · GitHub Actions · Docker

[![LinkedIn](https://img.shields.io/badge/LinkedIn-dhayv-blue?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dhayv/)
[![Blog](https://img.shields.io/badge/Blog-dev.to/dhayv-black?logo=dev.to)](https://dev.to/dhayv)
![Profile Views](https://komarev.com/ghpvc/?username=dhayv)

-----

## 🧠 GitOps & AI Infrastructure

![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?logo=argo&logoColor=white)

### [Azure RAG AI – Production AI Workload Platform](https://github.com/dhayv/azure-rag-app)

Built a production-ready AI application that actually works—not a tutorial, a real system with caching, retries, and guardrails.

- Deployed modular AI workload (FastAPI + Azure OpenAI + AI Search) with production-grade error handling
- Implemented GitOps control layer with Argo CD for declarative, auditable deployments
- Extended Azure GitOps patterns to complement AWS EKS/Terraform architectures
- **Infra repo:** [rag-infra](https://github.com/dhayv/rag-infra)

-----

## 🌩 Multi-Cloud Infrastructure

![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=white)

### [Hybrid Chatbot Platform – Cross-Cloud High Availability](https://github.com/dhayv/hybrid-chatbot-platform)

Eliminated single-cloud dependency by building failover across AWS and Azure—if one cloud goes down, traffic routes automatically.

- Co-engineered with [Dennis Teimuno](https://github.com/dteimuno)—two engineers, two clouds, one unified pipeline
- Implemented CloudFront multi-origin failover (EKS → AKS) for automatic cross-cloud routing
- Built reproducible IaC modules with VPC, IAM/RBAC, and declarative service manifests
- Deployed containerized chatbot across both AWS EKS and Azure AKS clusters

-----

## ☁️ AWS Kubernetes & Auto-Scaling

![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)

### [Secure AWS EKS in Private VPC](https://github.com/dhayv/aws-kubernetes-deploy) | [Blog Post](https://dev.to/dhayv/managing-kubernetes-in-a-private-aws-vpc-a-secure-and-automated-approach-4n4c)

Locked down Kubernetes access so nothing touches the cluster without proper credentials—no SSH, no public endpoints, no shortcuts.

- Provisioned EKS in private VPC with Terraform—zero public exposure
- Enforced IAM roles for all cluster access, eliminated static credentials
- Deployed containerized FastAPI app via ECR + Kubernetes manifests

### [Auto-Scaling Infrastructure](https://github.com/dhayv/autoscaling-group) | [Blog Post](https://dev.to/dhayv/from-502-to-200-building-a-auto-scaling-infrastructure-with-terraform-26dn)

Turned 502 errors into 200s by building infrastructure that scales itself when load spikes.

- Built multi-AZ autoscaling group with Nginx + ALB
- Configured automatic EC2 scaling based on CPU load
- Implemented CloudWatch monitoring for real-time visibility

-----

## 🌐 Azure CI/CD & Containerization

![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)

### [Azure FastAPI Deployment with CI/CD](https://github.com/dhayv/azure-cicd) | [Blog Post](https://dev.to/dhayv/how-to-deploy-a-fastapi-app-to-azure-with-docker-acr-and-github-actions-30bk)

Eliminated manual Azure deployments—code pushes to main, app deploys automatically.

- Containerized FastAPI → ACR → Azure App Service pipeline
- Automated deployments with GitHub Actions on every commit
- Secured registry access with Service Principals & GitHub Secrets

-----

## 🏗 Terraform & Infrastructure-as-Code

![Terraform](https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=white)
![S3](https://img.shields.io/badge/AWS_S3-569A31?logo=amazons3&logoColor=white)
![CloudFront](https://img.shields.io/badge/CloudFront-8C4FFF?logo=amazonaws&logoColor=white)

### [Serverless Blog Platform](https://github.com/dhayv/blogsite) | [Blog Post](https://dev.to/dhayv/building-a-cloud-native-blog-platform-with-terraform-11km)

Built a blog that costs almost nothing to host and deploys itself—no servers to manage, no manual uploads.

- Next.js + Terraform + S3 + CloudFront with near-zero hosting cost
- OIDC-secured GitHub Actions pipeline—no static AWS keys
- Zero-downtime static deploys with CDN caching

-----

## 🔄 CI/CD Pipelines

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![CodePipeline](https://img.shields.io/badge/AWS_CodePipeline-FF9900?logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

### [Kubernetes Deployment Pipeline](https://github.com/dhayv/kubectl-blog) | [Blog Post](https://dev.to/dhayv/build-a-secure-cicd-pipeline-for-amazon-eks-using-github-actions-and-aws-oidc-3b0m)

Removed static AWS keys from the deployment process entirely—OIDC handles authentication, no secrets to rotate.

- GitHub Actions → ECR → EKS with OIDC-based auth
- End-to-end FastAPI container deployment
- Eliminated credential rotation overhead

### [AWS EC2 CI/CD Pipeline](https://github.com/dhayv/ec2-deploy) | [Blog Post](https://dev.to/dhayv/building-a-cloud-native-blog-platform-with-terraform-11km)

Made EC2 deployments hands-off—push to GitHub, code lands on servers automatically.

- AWS CodePipeline + CodeBuild + CodeDeploy
- Zero-touch GitHub → EC2 delivery
- Quick rollbacks with versioned artifacts

### [Static Website Pipeline](https://github.com/dhayv/auto-deploy) | [Blog Post](https://dev.to/dhayv/building-a-cloud-native-blog-platform-with-terraform-11km)

Auto-deploys static sites on every commit—no manual S3 uploads, no forgetting to invalidate cache.

- CodePipeline → S3 with automatic deployment
- Built-in versioning + rollback capability

-----

## 📊 Monitoring & Observability

![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white)
![CloudWatch](https://img.shields.io/badge/AWS_CloudWatch-FF4F8B?logo=amazonaws&logoColor=white)

### [Grafana Monitoring on AWS](https://github.com/dhayv/Grafana-scripts) | [Blog Post](https://dev.to/dhayv/deploying-grafana-on-an-aws-ec2-instance2025-3li8)

Built dashboards that show what’s actually happening—CPU, network, disk, health—before users notice something’s wrong.

- Grafana + CloudWatch dashboards with stress-test visualizations
- IAM-based access control
- Real-time monitoring for proactive issue detection

-----

## 📜 Certifications

- **AWS Certified Solutions Architect – Associate**

-----

## 📈 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=dhayv&show_icons=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=dhayv&layout=compact)

-----

**Looking for a DevOps Engineer who ships reliable infrastructure?** [Let’s connect.](https://www.linkedin.com/in/dhayv/)