# Hi there, I'm Syed Abdullah Hussaini 👋
### Cloud Infrastructure & DevOps Engineer | AWS • Terraform • Kubernetes • GitOps

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/syed-abdullah-hussaini)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:devsyedabdullah@gmail.com)

---

### 🚀 About Me
Computer Science graduate focusing on **Cloud Infrastructure, Infrastructure as Code (IaC), and GitOps Delivery Pipelines**. 

- 🛠️ Hands-on experience architecting **modular multi-repo Terraform AWS infrastructure** (40+ resources across dev/prod with remote state locking).
- ☸️ Orchestrating **Kubernetes workloads with ArgoCD GitOps** (automated drift correction, self-healing, and zero-downtime rolling updates).
- ⚡ Building automated CI/CD workflows with **GitHub Actions matrix pipelines (<45s run time)** and **Jenkins**.
- 📈 Configuring system observability and alerts with **Prometheus, Grafana, and AWS CloudWatch**.

---

### 🛠️ Tech Stack & Toolchain

| Category | Technologies & Tools |
| :--- | :--- |
| **Cloud Platforms** | AWS (EC2, VPC, IAM, S3, KMS, DynamoDB, Lambda, CloudWatch) |
| **Infrastructure as Code** | Terraform (Modular HCL, Remote State S3/DynamoDB), Ansible |
| **Containers & GitOps** | Docker, Docker Compose, Kubernetes, ArgoCD |
| **CI / CD Automation** | GitHub Actions (Matrix CI/CD), Jenkins (Declarative Pipelines), Git |
| **Monitoring & Metrics** | Prometheus, Grafana, AWS CloudWatch |
| **Operating Systems & Scripting** | Linux (Ubuntu, SSH, Systemd), Bash, Python (Meta Certified), YAML |

---

### 🏆 Featured Projects

#### 1. [Enterprise Multi-Repo Terraform Infrastructure](https://github.com/Syed-Abdullah/infra-repo)
*Modular, production-grade AWS cloud infrastructure managed across independent repositories.*
- Split across **5 standalone Git repositories** (`infra-repo`, `vpc`, `ec2`, `iam-role`, `s3`) using semantic version tagging.
- Provisions **40+ AWS resources** across isolated `dev` and `prod` environments with remote state locking (S3 + DynamoDB).
- Security baselines: enforced **IMDSv2** (anti-SSRF), **KMS-encrypted EBS gp3 volumes**, and automated **GitHub Actions matrix CI/CD**.

#### 2. [Kubernetes GitOps & CI/CD Pipeline](https://github.com/Syed-Abdullah/Jenkins-CI-CD_app-repo)
*End-to-end automated software delivery pipeline from code commit to Kubernetes cluster.*
- Automated multi-node Kind cluster bootstrap on AWS EC2 using Terraform and Ansible roles.
- Implemented **ArgoCD** as a GitOps controller with `selfHeal: true` and `prune: true` for continuous declarative state reconciliation.
- Automated 4-stage Jenkins pipeline tagging Docker images with commit SHAs and executing zero-downtime rolling updates.
- Companion infrastructure repo: [CI-CD_infra-repo](https://github.com/Syed-Abdullah/CI-CD_infra-repo).

#### 3. [Blue Jay Travels — Production Platform](https://bluejaytravels.in)
*Commercial customer booking platform for an established transportation enterprise.*
- Built and launched with **React**, **Vite**, and **Supabase (PostgreSQL)** featuring Row-Level Security (RLS).
- Automated CI/CD deployment on Vercel with environment secret management.
- Source code: [bluejay-travels](https://github.com/Syed-Abdullah/bluejay-travels).

---

### 📬 Connect With Me
- 💼 **LinkedIn:** [linkedin.com/in/syed-abdullah-hussaini](https://linkedin.com/in/syed-abdullah-hussaini)
- 📧 **Email:** [devsyedabdullah@gmail.com](mailto:devsyedabdullah@gmail.com)
