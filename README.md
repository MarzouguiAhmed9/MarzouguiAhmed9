# Ahmed Marzougui | DevOps & Cloud Engineer 🚀

<div align="center">
  <img src="https://readme-typing-svg.demolab.com/?lines=DevOps%20Engineer;Cloud%20Platform%20Builder;Kubernetes%20%26%20Infrastructure%20Automation;Security%20%7C%20Scalability%20%7C%20Reliability&font=Fira%20Code&center=true&width=780&height=45&color=F75C7E&vCenter=true&size=22&pause=1000" />
  
  <br/>
  
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
  
  <br/><br/>
  <img src="https://komarev.com/ghpvc/?username=MarzouguiAhmed9&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile Views" />
</div>

---

## 👤 Profile

Final-year Engineering student in IT Infrastructure and Cloud Computing, seeking a 6-month internship starting January
2026. Skilled in automating CI/CD pipelines, cloud infrastructure, microservices, and ML workflows, with a proven focus on
building secure, reliable, and scalable systems that optimize project lifecycles and drive operational efficiency

- 📍 Tunis, Tunisia  
- 📱 +216 58 911 742  
- 📧 ahmed.marzougui@esprit.tn  
- 🌐 Portfolio: [marzouguiahmed9.github.io/portfolio](https://marzouguiahmed9.github.io/portfolio)  
- 💼 Open to opportunities starting **December 2025**

---

## 🧭 Quick Navigation

[Profile](#-profile) • [Experience](#-experience) • [Featured Projects](#-featured-projects) • [Full Project Gallery](#-full-project-gallery) • [Tech Radar](#-technical-skills) • [Education](#-education) • [Certifications](#-certifications) • [Languages](#-languages) • [Stats](#-github-stats)

---

## 💼 Experience

<details open>
<summary><b>DevSecOps Intern — ST2I, Tunisia (Jun 2025 – Sep 2025)</b></summary>
<br>

- Automated deployment of **8 Spring Boot microservices** on **OpenShift** using **Helm + Argo CD + GitLab CI**, reducing deployment time by **87%** across dev / stage / prod.  
- Built supply chain security: **SBOM (Syft)**, **vulnerability scanning (Trivy & Grype)**, **image signing (Cosign)**, enforced **RBAC & SonarQube quality gates** → **95% vulnerability reduction** and **35% code quality improvement**.  
- Achieved **99.5% uptime** via metrics + alerting dashboards (Prometheus + Grafana) and proactive SLO monitoring.  
- Standardized release promotion with Helm versioned rollbacks & policy checks.  
</details>

<details open>
<summary><b>DevOps Intern — SOCOOPEC, Tunisia (Jun 2024 – Jul 2024)</b></summary>
<br>

- Built internal **stock management platform** (Angular + Spring Boot + JWT + Swagger).  
- Automated frontend CI/CD with **GitHub Actions → AWS EC2**, cutting manual steps **80%** and achieving **~2 min build cycles**.  
- Introduced baseline monitoring & alert rules using **CloudWatch** (availability + resource usage).  
</details>

<details>
<summary><b>Full-Stack JavaScript Developer — AFTERCODE (Jun 2023 – Aug 2023)</b></summary>
<br>

- Developed interactive user interfaces with vanilla JavaScript, HTML, CSS.  
- Optimized UX via asynchronous data fetching and responsive layouts.  
</details>

---

## 🚀 Featured Projects

| Project | What It Solves | Impact | Stack |
|---------|----------------|--------|-------|
| **Terraform VPC Automation** | Standardized secure AWS network foundation. | ↓ Provision time **70%**, drift eliminated. | Terraform · AWS VPC · IAM · Remote State |
| **Automated KVM Virtual Lab** | Rapid reproducible local infra lab. | Setup **hours → <10 min**. | Ansible · KVM/libvirt · Cloud-init |
| **AWS 3‑Tier Architecture** | Resilient web/API baseline. | Multi-AZ HA + security tiering. | VPC · EC2 · ALB · ASG · Aurora | 
| **GitLab Helm Deployments (EKS)** | Gated Kubernetes delivery. | Faster rollout & safer rollback. | GitLab CI · Helm · EKS · RBAC |
| **Serverless File Sharing** | Secure collaboration platform. | 20–30 users, encrypted storage. | React · Cognito · Lambda · EFS |
| **Hybrid OpenStack Cloud** | Internal + burst compute platform. | Capacity visibility & flexibility. | OpenStack · K8s · AWS · Grafana |
| **Spring Boot on ECS Fargate** | Managed microservice runtime. | Zero-downtime releases & scaling. | ECS Fargate · CodePipeline |
| **Node.js K8s CI/CD** | Quality-focused delivery flow. | Faster feedback, fewer regressions. | Jenkins · K8s · Docker |
| **CI/CD Pipeline Optimization** | Build throughput improvements. | Deploys **<5 min**, manual ↓30%. | Jenkins · Caching · Telemetry |
| **Spam Detection ML Pipeline (DVC)** | Reproducible end-to-end ML workflow for spam classification. | Faster iteration; deterministic experiments; safe deployment readiness. | DVC · dvclive · Python · S3 · MLOps |
| **Service Health Checker API** | Lightweight active monitoring & metrics exposure. | Real-time visibility & rapid incident detection. | Go · Prometheus · Grafana · Docker |

---

## 📦 Full Project Gallery

<details open>
<summary><b>🧱 Infrastructure & Platform Engineering</b></summary>
<br>

### Terraform VPC Automation  
Infrastructure-as-Code modules to standardize secure AWS network foundations.  
- Reusable modules (VPC, subnets, routing, NAT, IGW, security boundaries).  
- Enforced tagging & CIDR conventions; multi-env parity (dev/stage/prod).  
- **Result:** 70% faster provisioning; near-zero config drift.  
**Stack:** Terraform • AWS VPC • IAM • Remote State (S3 + DynamoDB)

### AWS 3‑Tier Architecture  
Production-ready high-availability baseline.  
- Segmented public/private/db tiers with strict SG + NACL boundaries.  
- **ALB + Auto Scaling** for stateless resilience.  
- **Aurora MySQL (Multi-AZ)** for durability.  
**Stack:** AWS VPC • EC2 • ALB • ASG • Aurora MySQL • IAM • CloudWatch

### Hybrid OpenStack Private Cloud & AI Platform  
Internal cloud bridging on-prem workloads with AWS burst capacity.  
- Multi-node OpenStack (compute / networking / storage).  
- Hosted AI-oriented workloads: Kubernetes + DB layer.  
- Unified Grafana observability (capacity & performance).  
**Stack:** OpenStack • Ansible • Kubernetes • Docker • MySQL • AWS EC2/S3 • Grafana
</details>

<details>
<summary><b>⚙️ Automation & Virtualization</b></summary>
<br>

### Automated KVM Virtual Lab  
Local mini-cloud enabling repeatable ephemeral test setups.  
- Automated VM lifecycle (networking, SSH, users, packages) via Ansible + cloud-init.  
- **Setup time:** Hours → <10 minutes.  
**Stack:** Ansible • KVM/QEMU • libvirt • Cloud-init • Linux Networking
</details>

<details>
<summary><b>☁️ Cloud-Native Delivery & Runtime</b></summary>
<br>

### GitLab CI/CD Helm Deployments to EKS  
Policy-driven Kubernetes application delivery.  
- Pipeline: build → scan → chart lint → deploy (review → staging → prod).  
- Environment-specific `values.yaml` segregation + immutable image tags.  
**Stack:** GitLab CI • Helm • Amazon EKS • Docker • Registry • RBAC

### Spring Boot on AWS ECS Fargate  
Managed container runtime with scalable microservice deployment.  
- Pipeline: GitHub → CodePipeline → CodeBuild → ECR → ECS.  
- Rolling updates with autoscaling triggers + health checks.  
**Stack:** Spring Boot • Docker • ECS Fargate • ECR • CodePipeline • CodeBuild

### Node.js Kubernetes CI/CD Pipeline  
Quality-focused workflow with integrated security & notifications.  
- Static code analysis + container scan + deploy + Slack alerts.  
- Observability hooks for runtime metrics.  
**Stack:** Jenkins • Docker • Kubernetes • Node.js • Static Analysis • Slack API
</details>

<details>
<summary><b>🔐 Security, Reliability & Optimization</b></summary>
<br>

### CI/CD Pipeline Optimization  
Throughput and reliability improvements across build matrix.  
- Parallelized stages, caching layers, immutable artifact strategy.  
- **Deploy time:** <5 minutes; manual intervention ↓30%; MTTR improved via telemetry dashboards.  
**Stack:** Jenkins • Ansible • Docker • AWS EC2 • Caching • Monitoring

### Serverless Secure File Sharing Platform  
Low-ops encrypted collaboration stack.  
- Cognito-authenticated API Gateway + Lambda orchestration.  
- Encrypted storage using EFS + KMS; edge protection via WAF.  
- Designed for 20–30 concurrent users / 5–10 GB encrypted data.  
**Stack:** React • Cognito • API Gateway • Lambda • EFS • KMS • WAF • CloudWatch
</details>

---

## 🛰️ Technical Skills

<div align="center">
  
### Tech Stack Overview
| Domains | Focus Areas | Strength Highlights |
|---------|-------------|---------------------|
| Cloud & Platform | AWS, OpenStack | Multi-env architecture, networking, resilience |
| Containers & Orchestration | Docker, Kubernetes, OpenShift | Helm, Operators, RBAC, autoscaling |
| Infrastructure as Code | Terraform, Ansible, Helm | Modular design, policy & drift prevention |
| CI/CD & GitOps | GitLab CI, GitHub Actions, Argo CD, Jenkins | Secure pipelines, progressive delivery |
| Security & Supply Chain | Trivy, Grype, Syft, Cosign, SonarQube | SBOM, image signing, quality gates |
| Observability | Prometheus, Grafana, ELK, CloudWatch | Metrics, dashboards, alert tuning |

</div>

### 🧩 Categorized Skill Grid (Interactive)

<details open>
<summary><b>☁️ Cloud & Platform</b></summary>
<br>
<p align="center">
<img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white" />
<img src="https://img.shields.io/badge/OpenStack-ED1944?style=for-the-badge&logo=openstack&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
<img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>
</details>

<details open>
<summary><b>🐳 Containers & Orchestration</b></summary>
<br>
<p align="center">
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
<img src="https://img.shields.io/badge/OpenShift-EE0000?style=for-the-badge&logo=redhatopenshift&logoColor=white" />
<img src="https://img.shields.io/badge/EKS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white" />
<img src="https://img.shields.io/badge/ECS%20Fargate-FF9900?style=for-the-badge&logo=aws-fargate&logoColor=white" />
<img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white" />
</p>
</details>

<details open>
<summary><b>🧱 Infrastructure as Code & Automation</b></summary>
<br>
<p align="center">
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
<img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white" />
<img src="https://img.shields.io/badge/libvirt-222222?style=for-the-badge&logo=linux&logoColor=white" />
<img src="https://img.shields.io/badge/Cloud--init-7755CC?style=for-the-badge&logo=cloudflare&logoColor=white" />
<img src="https://img.shields.io/badge/Argo%20CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white" />
</p>
</details>

<details open>
<summary><b>🚀 CI/CD & Delivery</b></summary>
<br>
<p align="center">
<img src="https://img.shields.io/badge/GitLab%20CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" />
<img src="https://img.shields.io/badge/CodePipeline-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white" />
<img src="https://img.shields.io/badge/CodeBuild-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white" />
<img src="https://img.shields.io/badge/Artifact%20Governance-444444?style=for-the-badge&logo=artifacthub&logoColor=white" />
</p>
</details>

<details>
<summary><b>🔐 Security & Supply Chain</b></summary>
<br>
<p align="center">
<img src="https://img.shields.io/badge/Trivy-1904DA?style=for-the-badge&logo=aqua&logoColor=white" />
<img src="https://img.shields.io/badge/Grype-512BD4?style=for-the-badge&logo=github&logoColor=white" />
<img src="https://img.shields.io/badge/Syft-000000?style=for-the-badge&logo=github&logoColor=white" />
<img src="https://img.shields.io/badge/Cosign-2F855A?style=for-the-badge&logo=probot&logoColor=white" />
<img src="https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white" />
<img src="https://img.shields.io/badge/WAF-FF4F00?style=for-the-badge&logo=amazon-aws&logoColor=white" />
</p>
</details>

<details>
<summary><b>📊 Observability & Monitoring</b></summary>
<br>
<p align="center">
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" />
<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
<img src="https://img.shields.io/badge/ELK-005571?style=for-the-badge&logo=elasticsearch&logoColor=white" />
<img src="https://img.shields.io/badge/CloudWatch-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white" />
<img src="https://img.shields.io/badge/Dashboards-333333?style=for-the-badge&logo=datadog&logoColor=white" />
</p>
</details>

<details>
<summary><b>🧪 Programming & Frameworks</b></summary>
<br>
<p align="center">
<img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
<img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
<img src="https://img.shields.io/badge/Shell-121011?style=for-the-badge&logo=gnu-bash&logoColor=white" />
<img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" />
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
</p>
<p align="center">
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=spring&logoColor=white" />
<img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" />
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Symfony-000000?style=for-the-badge&logo=symfony&logoColor=white" />
<img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
<img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" />
<img src="https://img.shields.io/badge/REST-FF6F00?style=for-the-badge&logo=fastapi&logoColor=white" />
</p>
</details>

<details>
<summary><b>🗄️ Data & Storage</b></summary>
<br>
<p align="center">
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Aurora-00A1E0?style=for-the-badge&logo=amazon-aws&logoColor=white" />
<img src="https://img.shields.io/badge/EFS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white" />
<img src="https://img.shields.io/badge/S3-FF9900?style=for-the-badge&logo=amazon-s3&logoColor=white" />
</p>
</details>

> Designed for readability + visual grouping. Collapsible sections keep the README compact while allowing deeper exploration.

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
  <img src="https://img.shields.io/badge/Terraform-Basics-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
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
  <b>💼 Open to graduation internship opportunities starting December 2025</b><br/><br/>
  <i>Let’s build secure, observable, automated platforms.</i>
</div>
