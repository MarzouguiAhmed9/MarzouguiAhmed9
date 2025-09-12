# Ahmed Marzougui | DevOps & Cloud Engineer 🚀

<div align="center">
  <img src="https://readme-typing-svg.demolab.com/?lines=DevOps%20Engineer;Cloud%20Platform%20Builder;Kubernetes%20%26%20Infrastructure%20Automation;Security%20%7C%20Scalability%20%7C%20Reliability&font=Fira%20Code&center=true&width=650&height=45&color=f75c7e&vCenter=true&size=22&pause=1000" />
  <br/><br/>
  <a href="https://www.linkedin.com/in/ahmed-marzougui-cloud">
    <img src="https://img.shields.io/badge/LinkedIn-Ahmed%20Marzougui-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:ahmed.marzougui@esprit.tn">
    <img src="https://img.shields.io/badge/Email-ahmed.marzougui%40esprit.tn-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://marzouguiahmed9.github.io/portfolio">
    <img src="https://img.shields.io/badge/Portfolio-Live%20Site-0A66C2?style=for-the-badge&logo=firefox-browser&logoColor=white" />
  </a>
  <a href="https://github.com/MarzouguiAhmed9">
    <img src="https://img.shields.io/badge/GitHub-MarzouguiAhmed9-100000?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</div>

---

## 👤 Profile

Final-year engineering student in **IT Infrastructure & Cloud Computing**, seeking a **6‑month full-time graduation internship (Cloud / DevOps) starting December 2025**. Passionate about platform engineering, infrastructure automation, cloud security, and delivery reliability. Experienced with Kubernetes, OpenShift, Terraform, GitOps, observability and secure CI/CD supply chains.

- 📍 Tunis, Tunisia  
- 📱 +216 58 911 742  
- 📧 ahmed.marzougui@esprit.tn  
- 🌐 Portfolio: [marzouguiahmed9.github.io/portfolio](https://marzouguiahmed9.github.io/portfolio)  
- 💼 Open to opportunities starting **December 2025**

---

## 🔗 Quick Navigation
[Profile](#-profile) • [Experience](#-experience) • [Featured Projects](#-featured-projects) • [Full Project Gallery](#-full-project-gallery) • [Skills](#-technical-skills) • [Education](#-education) • [Certifications](#-certifications) • [Languages](#-languages) • [Stats](#-github-stats)

---

## 💼 Experience

<details open>
<summary><b>DevSecOps Intern — ST2I, Tunisia (Jun 2025 – Sep 2025)</b></summary>
<br>

- Automated deployment of **8 Spring Boot microservices** on **OpenShift** with **Helm + Argo CD + GitLab CI**, cutting deployment time by **87%** across dev/stage/prod.
- Implemented supply chain security: **SBOM (Syft)**, **vulnerability scanning (Grype & Trivy)**, **image signing (Cosign)**, enforced **RBAC + SonarQube + policy gates** → reduced exploitable vulnerabilities **95%**; improved code quality metrics **35%**.
- Delivered **99.5% uptime** on critical workloads via improved observability (Prometheus + Grafana dashboards, actionable alerts).
- Standardized environment promotion with progressive rollout strategy & rollback-ready Helm releases.
</details>

<details open>
<summary><b>DevOps Intern — SOCOOPEC, Tunisia (Jun 2024 – Jul 2024)</b></summary>
<br>

- Built an internal **stock management platform** (Angular + Spring Boot + JWT) with documented APIs (Swagger/OpenAPI).
- Automated frontend build & delivery via **GitHub Actions → AWS EC2**, reducing manual effort **80%**; ~**2‑minute reproducible builds**.
- Implemented foundational monitoring & alert signals with **CloudWatch** (availability + resource thresholds).
</details>

<details>
<summary><b>Full-Stack JavaScript Developer — AFTERCODE (Jun 2023 – Aug 2023)</b></summary>
<br>

- Delivered interactive, responsive front-end experiences using vanilla JavaScript, HTML, CSS.
- Improved UX through asynchronous data loading & minimal-latency updates (AJAX patterns).
</details>

---

## 🚀 Featured Projects

Curated high‑impact, infrastructure and delivery–focused builds.

| Project | What It Solves | Impact | Stack |
|---------|----------------|--------|-------|
| **Terraform VPC Automation** | Standardizes secure AWS networking foundations across environments. | ↓ Provision time **70%**, eliminated drift via module governance. | Terraform · AWS VPC · IAM · Remote State (S3+DynamoDB) |
| **Automated KVM Virtual Lab** | Rapid reproducible on-prem lab for DevOps experiments & testing. | Setup → **hours → <10 min**, accelerates iteration cycles. | Ansible · KVM/libvirt · Cloud-init · Linux Networking |
| **AWS 3‑Tier Architecture** | Production-ready baseline for scalable web/API workloads. | Fault-tolerant multi-AZ + hardened tiers. | VPC · EC2 · ALB · ASG · Aurora MySQL · IAM · CloudWatch |
| **GitLab Helm Deployments to EKS** | Policy-driven Kubernetes delivery with gated promotions. | Consistent releases, rollback confidence ↑. | GitLab CI · Helm · Amazon EKS · Docker · RBAC |
| **Serverless Secure File Sharing** | Low-ops collaboration platform with encryption & auth. | Secure 5–10 GB encrypted storage, 20–30 concurrent users. | React · Cognito · API Gateway · Lambda · EFS · KMS · WAF |
| **Hybrid OpenStack Private Cloud** | Internal cloud + AI experimentation platform w/ burst to AWS. | Unified workload + capacity visibility. | OpenStack · Ansible · Kubernetes · Docker · MySQL · AWS · Grafana |
| **Spring Boot on ECS Fargate** | Managed container runtime with automated delivery. | Zero-downtime rolling releases & autoscaling. | Spring Boot · Docker · ECS Fargate · ECR · CodePipeline |
| **Node.js K8s CI/CD Pipeline** | Secure, observable delivery workflow for microservices. | Faster feedback, reduced regression risk. | Jenkins · Docker · Kubernetes · Static Analysis · Slack API |
| **CI/CD Pipeline Optimization** | Performance tuning for large build matrix. | Deploy < **5 min**, manual intervention ↓ **30%**. | Jenkins · Ansible · Docker · AWS EC2 · Caching · Monitoring |

---

## 📦 Full Project Gallery

<details open>
<summary><b>🧱 Infrastructure & Platform Engineering</b></summary>
<br>

### Terraform VPC Automation  
Infrastructure-as-Code modules to standardize secure AWS network foundations.  
- Reusable modules: VPC, subnets (public/private), route tables, IGW, NAT, security boundaries.  
- Enforced: tagging strategy, CIDR governance, multi-env layout (dev/stage/prod).  
- Result: **70% faster provisioning**, near-zero config drift.  
**Stack:** Terraform • AWS VPC • IAM • Remote State (S3 + DynamoDB)

### AWS 3‑Tier Architecture  
Production-ready baseline for resilient web/API workloads.  
- Segmented tiers (public, private, db) + tightened security groups / NACLs.  
- **ALB + Auto Scaling** for stateless layer resiliency.  
- **Multi-AZ Aurora MySQL** for HA & durability.  
**Stack:** AWS VPC • EC2 • ALB • ASG • Aurora MySQL • IAM • CloudWatch

### Hybrid OpenStack Private Cloud & AI Platform  
Educational + compute platform bridging private infra and AWS for burst.  
- Multi-node OpenStack (compute, networking, storage).  
- Internal Kubernetes + MySQL for AI/local workloads.  
- Central Grafana dashboards (capacity, performance).  
**Stack:** OpenStack • Ansible • Kubernetes • Docker • MySQL • AWS EC2/S3 • Grafana

</details>

<details>
<summary><b>⚙️ Automation & Virtualization</b></summary>
<br>

### Automated KVM Virtual Lab  
Local "mini cloud" enabling repeatable ephemeral test environments.  
- Orchestrated VM lifecycle (network/user bootstrap, SSH keys, packages) via Ansible + cloud-init.  
- Reduced environment setup from **hours → <10 minutes**.  
- Supports CI/CD, container runtime and clustering experiments.  
**Stack:** Ansible • KVM/libvirt • Cloud-init • Linux Networking

</details>

<details>
<summary><b>☁️ Cloud-Native Delivery & Runtime</b></summary>
<br>

### GitLab CI/CD Helm Deployments to EKS  
Policy-driven Kubernetes delivery with environment-specific values.  
- Pipeline stages: build → scan → lint → deploy (review → staging → prod gates).  
- Enhanced rollback confidence via chart versioning & immutable images.  
**Stack:** GitLab CI • Helm • Amazon EKS • Docker • Registry • RBAC

### Spring Boot on AWS ECS Fargate  
Containerized microservice with streamlined continuous delivery.  
- Pipeline: GitHub → CodePipeline → CodeBuild → ECR → ECS (rolling updates).  
- Autoscaling + health checks for reliability.  
**Stack:** Spring Boot • Docker • ECS Fargate • ECR • CodePipeline • CodeBuild

### Node.js Kubernetes CI/CD Pipeline  
End-to-end pipeline with quality enforcement & observability.  
- Static analysis, container scanning, runtime deploy stages.  
- Slack notifications & operational metrics integration.  
**Stack:** Jenkins • Docker • Kubernetes • Node.js • Static Analysis • Slack API

</details>

<details>
<summary><b>🔐 Security, Reliability & Optimization</b></summary>
<br>

### CI/CD Pipeline Optimization  
Refined delivery platform for faster, more reliable iterative releases.  
- Introduced caching layers, parallelization, artifact immutability.  
- Achieved deploys **<5 minutes**; manual interventions ↓ **30%**; improved MTTR with telemetry.  
**Stack:** Jenkins • Ansible • Docker • AWS EC2 • Monitoring

### Serverless Secure File Sharing Platform  
Scalable collaboration with tenant-level access guarantees.  
- **Cognito** for auth; **API Gateway + Lambda** orchestrating file lifecycle.  
- **EFS + KMS** for encrypted at-rest storage; **WAF** for edge protection.  
- Designed for 20–30 concurrent users, 5–10 GB encrypted data footprint.  
**Stack:** React • Cognito • API Gateway • Lambda • EFS • KMS • WAF • CloudWatch

</details>

---

## 🛠️ Technical Skills

<details open>
<summary><b>Programming</b></summary>
<br>
Python · Java · JavaScript · PHP · C / C++ · Shell Script · Rust · Go
</details>

<details open>
<summary><b>Cloud / DevOps</b></summary>
<br>
AWS · Terraform · OpenStack · Kubernetes · Docker · Argo CD · Helm · GitLab CI · GitHub Actions · Jenkins · OpenShift · Ansible · Grafana · Prometheus · ELK Stack
</details>

<details>
<summary><b>Frameworks & Platforms</b></summary>
<br>
Spring Boot · Angular · Symfony · .NET · React · Microservices Architecture · REST / JWT · Swagger / OpenAPI
</details>

<details>
<summary><b>Virtualization & Systems</b></summary>
<br>
QEMU/KVM · libvirt · Cloud-init · Linux System Administration · Container Image Hardening · RBAC & Policy
</details>

<details>
<summary><b>Security & Reliability</b></summary>
<br>
SBOM (Syft) · Vulnerability Scanning (Grype, Trivy) · Image Signing (Cosign) · CI/CD Quality Gates · Supply Chain Security · WAF · Secrets Management · TLS · Observability (Metrics / Dashboards / Alerts)
</details>

---

## 🎓 Education

**Private Higher School of Engineering and Technologies (ESPRIT), Tunisia**  
Integrated Master’s-level Engineering Program in IT Infrastructure & Cloud Computing (2022 – Present)

**Higher Institute of Applied Sciences and Technology of Mahdia (ISSATM), Tunisia**  
Preparatory Cycle in Mathematics & Physics (2019 – 2022)

---

## 📜 Certifications

<div align="center">
  <img src="https://img.shields.io/badge/AWS-Academy%20Cloud%20Foundations-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-Basics-5835CC?style=for-the-badge&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-Programming%20Fundamentals-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
</div>

---

## 🌐 Languages

<div align="center">
  <img src="https://img.shields.io/badge/Arabic-C2-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/French-B2-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/English-B2-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/German-A2-blue?style=for-the-badge" />
</div>

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MarzouguiAhmed9&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub Stats" />
  <br/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=MarzouguiAhmed9&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MarzouguiAhmed9&theme=tokyonight&hide_border=true&layout=compact" alt="Top Languages" />
</div>

---

## 🏆 GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=MarzouguiAhmed9&theme=algolia&no-frame=true&column=7" alt="GitHub Trophies" />
</div>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=MarzouguiAhmed9&label=Profile%20views&color=0e75b6&style=flat" alt="Profile Views" />
  <br/><br/>
  <b>💼 Open to graduation internship opportunities starting December 2025</b>
</div>

---

### 🧩 Suggestions (Optional Next Enhancements)
- Add architecture diagrams (Mermaid or linked images) for top 2–3 infra projects.
- Pin repos: `Terraform VPC`, `automated-kvm-virtual-lab`, `Collaborative-File-Sharing-Platform`.
- Add a “Learning Now” ribbon (e.g., Service Mesh, eBPF, Crossplane).
- Add Shields for build status from your active pipelines (if public).

Let me know if you’d like:
1. A condensed recruiter variant (1 screen length)
2. A French version
3. A PR opened automatically to update your profile repo

Just ask and I’ll generate it.
