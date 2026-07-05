# Zhamoliddin Zhalolov

**Platform / DevOps Engineer** building reliable, scalable and secure cloud platforms.

📍 Boston, Massachusetts  
🚀 AWS • Kubernetes • Terraform • GitOps • CI/CD • Cloud Automation

## About Me

I am a Platform / DevOps Engineer focused on designing and operating AWS infrastructure, Kubernetes platforms, delivery pipelines and GitOps workflows.

My work and current projects focus on:

- Production-style Amazon EKS platforms
- Reusable Terraform infrastructure modules
- Kubernetes workload and node autoscaling
- GitHub Actions CI/CD pipelines
- Argo CD GitOps deployments
- Cloud security and least-privilege access
- Monitoring, observability and incident response
- Python and AWS Lambda automation
- AI-powered applications and developer tooling

## Featured Platform Project

I am building an end-to-end AWS EKS platform that demonstrates how infrastructure, Kubernetes, CI/CD, GitOps, autoscaling, security and observability integrate together.

### Architecture

```text
Developer
    ↓
GitHub
    ↓
GitHub Actions
    ├── Test
    ├── Build Docker image
    ├── Trivy security scan
    └── Push image to Amazon ECR
            ↓
GitOps repository
            ↓
Argo CD
            ↓
Amazon EKS
    ├── Application workloads
    ├── Karpenter autoscaling
    ├── AWS Load Balancer Controller
    ├── External Secrets
    └── Monitoring and observability


