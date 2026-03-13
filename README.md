<!-- ====================== ENTERPRISE DEVOPS PROFILE ====================== -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=Satyajit%20Barik&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Senior%20DevOps%20Engineer%20|%20Kubernetes%20|%20Cloud%20Infrastructure%20|%20Automation&descAlignY=58&descAlign=50"/>
</p>

---

# 👋 Satyajit Barik

### Senior DevOps Engineer | Kubernetes Specialist | Cloud Infrastructure Architect

---

## 🧠 Executive Summary

DevOps Engineer with **1+ years of hands-on production experience** designing, automating, and operating scalable cloud-native systems.

Experienced in building Kubernetes clusters from scratch, automating infrastructure using Terraform, managing distributed storage systems, and leading cloud migrations (Azure → Utho Cloud).

Focused on reliability, automation, performance optimization, and production-grade architecture.

---

# ⚙️ Core Expertise

- Kubernetes cluster bootstrapping (kubeadm)
- Cloud migration & workload portability
- Infrastructure as Code (Terraform modular architecture)
- CI/CD automation & GitOps workflows
- Linux system administration & performance tuning
- Storage engineering (RBD, DRBD, Linstor, Ceph)
- Object Storage (S3 compatible)
- Production troubleshooting & root cause analysis
- Reverse proxy & load balancing architecture
- High availability system design

---

# 🛠 Enterprise DevOps Technology Stack

---

## ☁️ Cloud Platforms

<p align="center">
  <img src="https://skillicons.dev/icons?i=azure,aws,gcp" />
</p>

**Additional Cloud Experience:**  
Utho Cloud

---

## 📦 Containerization & Orchestration

<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,helm,argo" />
</p>

**Also Experienced With:**  
Kops • Docker Swarm • FluxCD • Tekton • Spinnaker • OpenShift

---

## 🏗 Infrastructure as Code & Configuration Management

<p align="center">
  <img src="https://skillicons.dev/icons?i=terraform,ansible,aws" />
</p>

**Also Experienced With:**  
Terraform Cloud • AWS CloudFormation

---

## 🚀 CI/CD & DevOps Tooling

<p align="center">
  <img src="https://skillicons.dev/icons?i=jenkins,githubactions,gitlab,azuredevops,argo" />
</p>

**Also Experienced With:**  
GitLab CI/CD • Argo Workflows • Bitbucket Pipelines

---

## ⚡ Serverless & Event-Driven

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,azure" />
</p>

**Technologies:**  
AWS Lambda • Azure Functions • OpenFaaS • Apache OpenWhisk

---

## 🌐 Web Servers, Caching & Load Balancing

<p align="center">
  <img src="https://skillicons.dev/icons?i=nginx,apache,redis" />
</p>

**Also Experienced With:**  
HAProxy • Varnish

---

## 📊 Monitoring, Logging & Observability

<p align="center">
  <img src="https://skillicons.dev/icons?i=prometheus,grafana,elasticsearch,kibana,logstash" />
</p>

**Also Experienced With:**  
Zabbix • Nagios • Azure Monitor • Datadog • New Relic

---

## 🗄 Databases & Data Systems

<p align="center">
  <img src="https://skillicons.dev/icons?i=mysql,postgres,mongodb,redis" />
</p>

**Also Experienced With:**  
MariaDB • AWS DynamoDB

---

## 🔐 Security & Secrets Management

<p align="center">
  <img src="https://skillicons.dev/icons?i=vault,aws,azure" />
</p>

**Technologies:**  
HashiCorp Vault • OpenBao • Azure Key Vault • AWS Secrets Manager  
RBAC • SSL/TLS • OAuth

---

## 💻 Scripting & Markup

<p align="center">
  <img src="https://skillicons.dev/icons?i=bash,powershell,python" />
</p>

YAML • JSON • Shell Scripting

---

## 🔁 Version Control Systems

<p align="center">
  <img src="https://skillicons.dev/icons?i=git,github,gitlab,bitbucket,azuredevops" />
</p>

Azure Repos

---

## 🖥 Operating Systems

<p align="center">
  <img src="https://skillicons.dev/icons?i=linux,windows" />
</p>

Ubuntu • CentOS • RHEL • Debian • Windows Server • macOS

---

## 🧠 System Administration & Storage Engineering

- User & Permission Management
- Package Management (apt, yum, dnf)
- Process & Service Management (systemd)
- Cron Jobs
- File Systems & Storage Management
- DRBD • ZFS • LVM
- Linstor (DRBD-based Storage)
- Linbit Storage Solutions

---

## 🏢 Virtualization & Infrastructure

- Hyper-V
- KVM
- Proxmox VE
- VM Provisioning & Migration
- Rack & Stack Deployment
- RAID Configuration
- BIOS/UEFI Setup
- iDRAC / iLO Management
- Hardware Troubleshooting

---

## 🌐 Networking & Infrastructure Design

- VPC Architecture
- Subnets
- Security Groups
- Network Security Groups (NSGs)
- VPN Configuration
- Load Balancers
- Firewall Configuration
- DNS Management
- TCP/IP Networking
---

# 🚀 Enterprise Projects

---

## 1️⃣ Kubernetes Cluster Migration (Azure → Utho Cloud)

### Objective
Migrate production Kubernetes workloads from Azure to Utho Cloud with minimal downtime and optimized storage configuration.

### Architecture Overview

```mermaid
flowchart LR
    Dev[Developer] --> Git
    Git --> Jenkins
    Jenkins --> ContainerRegistry
    ContainerRegistry --> AKSCluster
    AKSCluster -. Migration .-> UthoK8s
    UthoK8s --> ObjectStorage
    UthoK8s --> EndUsers
