# 💫 About Me

Hi, I’m **Andrey** — a Platform Engineer and AI Infrastructure Architect focused on production-grade platforms for private AI workloads.

I combine Kubernetes, GitOps, Infrastructure as Code, Observability and AI Runtime Engineering to build secure, scalable and governable AI platforms.

🔧 I design **runtime and control-plane platforms** with Kubernetes, OpenTelemetry, KServe, vLLM, KEDA, Argo CD and Terraform.

![DevOps animation](devops-look.gif)

🧠 Currently focused on AI inference routing, GenAI observability, cost governance, risk scoring and policy-driven operations.

![DevOps animation](devops-work.gif)

> **"AI infrastructure should be observable, governable and boring in production."**

---

## 🏆 Recognition

[**Cloud Native Rockstar 2026**](https://www.cloudnativeconference.de/rockstars-2026)

<p align="center">
  <a href="https://www.cloudnativeconference.de/rockstars-2026">
    <img src="./cloud-native-rockstar-2026.gif" alt="Cloud Native Rockstar 2026 Nominee" width="360">
  </a>
</p>

---

## 🚀 What I Do

- 🧱 Build cloud-native and AI-native platforms with Kubernetes, GitOps and Infrastructure as Code
- 🧠 Design AI runtime layers for private LLM inference, routing, fallback and autoscaling
- 📡 Implement OpenTelemetry-based observability for infrastructure and GenAI workloads
- 🛡️ Build governance workflows for cost control, risk scoring, approvals and operational policy
- 🎯 Architect GitOps delivery with Argo CD, Argo Rollouts, Helm and Terraform

![DevOps animation](devops-caffe.gif)

> ⚠️ Fun fact: the best infrastructure is still the one nobody notices during business hours.

---

## 🚀 AI Platform Portfolio

Two repositories demonstrate the complete operating model for private AI workloads:

```mermaid
flowchart TB
  Users["Users / OpenAI SDKs"] --> Runtime["AI Runtime Platform"] --> Models["Models: Ollama / vLLM / KServe"]
  Control["AI Infrastructure Control Plane\nObservability · Governance · Forecasting · Policy"] -. operates .-> Runtime
```

### 🥇 [AI Runtime Platform](https://github.com/justrunme/ai-runtime-platform)

[![Animated preview of the AI Runtime Platform Demo](https://github.com/justrunme/ai-runtime-platform/blob/main/docs/images/runtime-demo/full-runtime-decision-loop.gif?raw=true)](https://github.com/justrunme/ai-runtime-platform)

_Production-grade AI Runtime Layer for private LLM workloads._

- OpenAI-compatible APIs
- Runtime Decision Engine for request-time model selection
- Health-aware and cost-aware routing
- Canary deployments and fallback policies
- Ollama, vLLM and KServe integration
- KEDA autoscaling and GitOps deployment path
- OpenTelemetry GenAI telemetry

### 🥈 [AI Infrastructure Control Plane](https://github.com/justrunme/ai-infra-control-plane)

[![Animated preview of the AI Infrastructure Control Plane](https://github.com/justrunme/ai-infra-control-plane/blob/main/docs/videos/previews/hero-overview.gif?raw=true)](https://github.com/justrunme/ai-infra-control-plane)

_Governance and Operations Platform for AI Infrastructure._

- AI observability and OpenTelemetry telemetry
- Forecasting and digital twin topology
- Cost governance and risk scoring
- Approval workflows and policy management
- Grafana, Loki and GitOps operations

Together, they show a complete AI Platform architecture: the Runtime Platform executes AI workloads, while the Control Plane observes, governs, predicts and controls them.

---

## 🧱 Previous Infrastructure Projects

Earlier hands-on work in cloud automation, GitOps, security and platform reliability:

### 🚀 Infrastructure & GitOps

- 🔄 **[Self-Healing Infrastructure with Chaos Engineering](https://github.com/justrunme/self-healing-infrastructure-chaos-engineering)**  
  _Kubernetes + LitmusChaos + Prometheus — auto-recovery pipelines and dashboards._

- 📦 **[GitOps Duel: ArgoCD vs Flux](https://github.com/justrunme/gitops-duel-argocd-vs-flux)**  
  _Side-by-side GitOps deployment comparison with ArgoCD and FluxCD on Kind._

- ☁️ **[Multi-Cloud IaC with Terraform + Terragrunt](https://github.com/justrunme/k8s-terraform)**  
  _Reusable infrastructure stacks across AWS and Azure using Terragrunt modules._

---

### 🛡️ Security & Observability

- 🔍 **[AWS Security Audit with Prowler](https://github.com/justrunme/prowler)**  
  _Automated scanning with Prowler + integration with Security Hub + GitHub Actions._

- 📊 **[Cloud-Native GitOps Platform with ArgoCD, Terraform, Monitoring & Security](https://github.com/justrunme/cloud-devops-platform)**  
  _Prometheus, Loki, Grafana and Jaeger setup with alerting and dashboards._

---

> 💡 Want more? Visit [github.com/justrunme?tab=repositories](https://github.com/justrunme?tab=repositories) for future experiments.

## 🤝 Let’s Work Together

🔭 **Open to collaboration** on:

- Platform Engineering / Developer Experience
- AI Infrastructure Architecture
- Private LLM Runtime Platforms
- GenAI Observability and Runtime Governance
- Kubernetes Operators / Controllers
- Cloud-native compliance & security
- Multi-cloud architecture (AWS / Azure / GCP)

🌍 [**Visit my Lab → Self-Healing Infrastructure with Chaos Engineering**](https://justrunme.github.io/self-healing-infrastructure-chaos-engineering/)  
_for tools, experiments, and ideas that shouldn't run as root._

---

## 🌱 Currently Building

![DevOps animation](devops-tools.gif)

- 🧠 **AI Runtime Decision Engines** for model routing, fallback, health and cost-aware inference
- 📡 **OpenTelemetry GenAI Observability** for traces, metrics and runtime-level AI signals
- 🧭 **AI Infrastructure Control Planes** for governance, forecasting, approvals and policy updates
- 🛡️ **Policy-Driven AI Governance** with OPA, Rego, Conftest and GitOps workflows
- 🛡️ **eBPF** for observability and zero-trust runtime security

---

## 💬 Ask Me About

- 🤖 AI Runtime Platforms, inference routing, KServe, vLLM and KEDA
- 📡 OpenTelemetry, GenAI observability, Grafana and Loki
- 🧭 AI governance, cost governance, risk scoring and approval workflows
- 🔄 GitOps, Helm, Argo CD, Argo Rollouts and Terraform
- ⚙️ CI/CD with GitHub Actions and GitLab CI
- 🛡️ Secure CloudOps and SRE practices
- 📬 Chat with me on [Telegram → @justrunme](https://t.me/justrunme)

---

## 🧰 Tech Stack Highlights

### 🤖 AI Platform Engineering

![KServe](https://img.shields.io/badge/-KServe-326ce5?style=for-the-badge&logo=kubernetes&logoColor=white)
![vLLM](https://img.shields.io/badge/-vLLM-7C3AED?style=for-the-badge&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/-Ollama-111827?style=for-the-badge&logo=ollama&logoColor=white)
![OpenAI API](https://img.shields.io/badge/-OpenAI%20API%20Compatible-10A37F?style=for-the-badge&logo=openai&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/-OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white)
![OpenTelemetry GenAI](https://img.shields.io/badge/-OpenTelemetry%20GenAI-000000?style=for-the-badge&logo=opentelemetry&logoColor=white)
![KEDA](https://img.shields.io/badge/-KEDA-326ce5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Argo Rollouts](https://img.shields.io/badge/-Argo%20Rollouts-FB5012?style=for-the-badge&logo=argo&logoColor=white)
![OPA](https://img.shields.io/badge/-OPA-7D9199?style=for-the-badge&logo=openpolicyagent&logoColor=white)
![Rego](https://img.shields.io/badge/-Rego-5C4EE5?style=for-the-badge&logo=openpolicyagent&logoColor=white)
![Conftest](https://img.shields.io/badge/-Conftest-1f2937?style=for-the-badge&logo=openpolicyagent&logoColor=white)

### 🧩 AI Platform Capabilities

![AI Governance](https://img.shields.io/badge/-AI%20Governance-6f42c1?style=for-the-badge&logo=github&logoColor=white)
![Cost Governance](https://img.shields.io/badge/-Cost%20Governance-0f766e?style=for-the-badge&logo=grafana&logoColor=white)
![Risk Scoring](https://img.shields.io/badge/-Risk%20Scoring-b91c1c?style=for-the-badge&logo=prometheus&logoColor=white)
![Approval Workflows](https://img.shields.io/badge/-Approval%20Workflows-7c2d12?style=for-the-badge&logo=githubactions&logoColor=white)
![Digital Twin](https://img.shields.io/badge/-Digital%20Twin-4f46e5?style=for-the-badge&logo=grafana&logoColor=white)
![Forecasting](https://img.shields.io/badge/-Forecasting-0f172a?style=for-the-badge&logo=grafana&logoColor=white)
![Runtime Decision Engines](https://img.shields.io/badge/-Runtime%20Decision%20Engines-1f2937?style=for-the-badge&logo=fastapi&logoColor=white)
![Multi-Model Routing](https://img.shields.io/badge/-Multi--Model%20Routing-2563eb?style=for-the-badge&logo=kubernetes&logoColor=white)
![Health-Aware Routing](https://img.shields.io/badge/-Health--Aware%20Routing-16a34a?style=for-the-badge&logo=prometheus&logoColor=white)
![Cost-Aware Routing](https://img.shields.io/badge/-Cost--Aware%20Routing-0f766e?style=for-the-badge&logo=grafana&logoColor=white)
![Canary Deployments](https://img.shields.io/badge/-Canary%20Deployments-FB5012?style=for-the-badge&logo=argo&logoColor=white)
![Model Fallback](https://img.shields.io/badge/-Model%20Fallback-7c3aed?style=for-the-badge&logo=fastapi&logoColor=white)

### ☁️ Cloud & Container
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326ce5?style=for-the-badge&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/-Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/-GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Minikube](https://img.shields.io/badge/-Minikube-F4A261?style=for-the-badge&logo=kubernetes&logoColor=white)
![Kind](https://img.shields.io/badge/-Kind-1E90FF?style=for-the-badge&logo=kubernetes&logoColor=white)
![Lambda](https://img.shields.io/badge/-AWS%20Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![On-Premise](https://img.shields.io/badge/-On--Premise-444444?style=for-the-badge&logo=serverfault&logoColor=white)

### 🔧 IaC & GitOps
![Terraform](https://img.shields.io/badge/-Terraform-5C4EE5?style=for-the-badge&logo=terraform&logoColor=white)
![Terragrunt](https://img.shields.io/badge/-Terragrunt-4043c0?style=for-the-badge&logo=terraform&logoColor=white)
![Pulumi](https://img.shields.io/badge/-Pulumi-3C4C99?style=for-the-badge&logo=pulumi&logoColor=white)
![AWS CDK](https://img.shields.io/badge/-AWS%20CDK-4B612C?style=for-the-badge&logo=amazonaws&logoColor=white)
![CloudFormation](https://img.shields.io/badge/-CloudFormation-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Ansible](https://img.shields.io/badge/-Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![ArgoCD](https://img.shields.io/badge/-ArgoCD-FB5012?style=for-the-badge&logo=argo&logoColor=white)
![Helm](https://img.shields.io/badge/-Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![Kustomize](https://img.shields.io/badge/-Kustomize-326ce5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Kured](https://img.shields.io/badge/-Kured-326ce5?style=for-the-badge&logo=kubernetes&logoColor=white)

### 🔍 Observability & Security
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/-Loki-0D1117?style=for-the-badge&logo=grafana&logoColor=white)
![Jaeger](https://img.shields.io/badge/-Jaeger-00B3E3?style=for-the-badge&logo=jaeger&logoColor=white)
![eBPF](https://img.shields.io/badge/-eBPF-black?style=for-the-badge&logo=ebpf&logoColor=white)
![Trivy](https://img.shields.io/badge/-Trivy-0F92FF?style=for-the-badge&logo=aqua&logoColor=white)
![Prowler](https://img.shields.io/badge/-Prowler-EC1C24?style=for-the-badge&logo=amazonaws&logoColor=white)
![AWS Security Hub](https://img.shields.io/badge/-AWS%20Security%20Hub-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)

### ⚙️ CI/CD & SCM
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![GitLab](https://img.shields.io/badge/-GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Bitbucket](https://img.shields.io/badge/-Bitbucket-0052CC?style=for-the-badge&logo=bitbucket&logoColor=white)
![Jenkins](https://img.shields.io/badge/-Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

### 🧠 AI, Data & DB
![Weaviate](https://img.shields.io/badge/-Weaviate-3B3B98?style=for-the-badge&logo=data&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![DynamoDB](https://img.shields.io/badge/-DynamoDB-4053D6?style=for-the-badge&logo=amazonaws&logoColor=white)

### 🧑‍💻 Programming & Automation
![Go](https://img.shields.io/badge/-Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/-Python-306998?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Zsh](https://img.shields.io/badge/-Zsh-89e051?style=for-the-badge&logo=gnu&logoColor=black)

### 📋 Project & Collaboration
![Jira](https://img.shields.io/badge/-Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Atlassian](https://img.shields.io/badge/-Atlassian-172B4D?style=for-the-badge&logo=atlassian&logoColor=white)

---

## 📈 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=justrunme&theme=transparent&hide_border=false&include_all_commits=true&count_private=true)
![GitHub Streak](https://streak-stats.demolab.com?user=justrunme&theme=transparent&hide_border=false)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=justrunme&layout=compact&theme=transparent&hide_border=false)

---

## 📟 Profile Counter

![Profile Views](https://komarev.com/ghpvc/?username=justrunme&color=6f42c1&style=flat-square)
