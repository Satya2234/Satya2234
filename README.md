![Logo](https://github.com/Satya2234/Satya2234/blob/main/Satyajit-Barik_Banner.png)

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

## ☁️ Cloud & Platform Engineering

<p align="center">
  <img src="https://skillicons.dev/icons?i=azure,openshift,kubernetes,docker,containerd,linux,nginx,apache,haproxy&perline=9" />
</p>

---

## ⚙️ Infrastructure as Code & Automation

<p align="center">
  <img src="https://skillicons.dev/icons?i=terraform,ansible,bash,python,git,githubactions&perline=6" />
</p>

---

## 🚀 CI/CD & GitOps

<p align="center">
  <img src="https://skillicons.dev/icons?i=jenkins,argo,helm&perline=6" />
</p>

---

## 🔐 Security & Secrets Management

<p align="center">
  <img src="https://skillicons.dev/icons?i=vault&perline=6" />
</p>

---

## 📊 Monitoring, Logging & Observability

<p align="center">
  <img src="https://skillicons.dev/icons?i=prometheus,grafana,elasticsearch,kibana,logstash&perline=6" />
</p>

---

## 💾 Storage & Distributed Systems

<p align="center">
  <img src="https://skillicons.dev/icons?i=ceph,redis,rabbitmq,mysql,mongodb&perline=6" />
</p>

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
