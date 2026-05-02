<div align="center">

# 👨‍💻 Infrastructure Engineer Who Ships to Production

[![Status](https://img.shields.io/badge/Status-Shipping%20to%20Prod-success?style=flat-square&logo=github)](https://github.com/Devzane)
[![Learning](https://img.shields.io/badge/Learning-Cloud%20at%20Scale-blue?style=flat-square&logo=coursera)](https://www.coursera.org/specializations/building-cloud-computing-solutions-at-scale)
[![Open to Roles](https://img.shields.io/badge/Open%20to-Cloud%2FMLOps%20Roles-orange?style=flat-square&logo=handshake)](mailto:your-sulaimananabdulmuheez@gmail.com)

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

</div>

---

## 🚀 About Me

> I turn AI prototypes into bulletproof cloud deployments. Former agency founder who got tired of duct-tape solutions—now I build the immutable, code-first infrastructure that lets engineering teams move fast without breaking prod. **Terraform → Docker → ECS Fargate → Continuous Deployment.**

Currently deploying ML inference pipelines at scale. Previously built and operated infrastructure for enterprise AI automation clients as agency founder.

**Mechatronics Engineering student.** I understand both the metal and the cloud—from edge hardware to distributed systems.

---

## ⚡ What I Build

### Production-Grade MLOps Pipelines
Containerized Python/FastAPI services → GitHub Actions CI/CD → AWS ECS Fargate with zero-downtime rolling updates. Not a tutorial project—this infrastructure processed **50K+ API calls** for real customers.

### Immutable Infrastructure as Code
Modular Terraform blueprints for highly available AWS environments. Recreate the entire VPC/subnet/IAM stack in **8 minutes** with `terraform apply`. Treat infrastructure like cattle, not pets.

### Edge-to-Cloud ML Deployment
AWS IoT Greengrass pipelines shipping computer vision models to hardware. Bridged the gap between cloud-trained PyTorch models and real-time edge inference with over-the-air updates.

---

## 🏗️ Featured Projects

### 🔥 Vectra Automation Engine
**The Problem:** Manual deployments taking 45+ minutes, risk of downtime during updates, no automated testing  
**The Solution:** End-to-end CI/CD pipeline with zero-downtime deployments

```mermaid
graph LR
    A[GitHub PR] -->|Triggers| B[GitHub Actions]
    B -->|Pytest Suite| C{Tests Pass?}
    C -->|✅ Yes| D[Build Docker Image]
    C -->|❌ No| E[Block Deploy]
    D -->|Push| F[AWS ECR]
    F -->|Pull| G[ECS Fargate Service]
    G -->|Rolling Update| H[Application Load Balancer]
    H -->|Route Traffic| I[FastAPI + Gemini API]
    
    style B fill:#2088FF
    style G fill:#FF9900
    style I fill:#00D084
```

**Impact:**
- ⚡ Deployment time: **45 minutes → 8 minutes** (82% reduction)
- 🛡️ **Zero customer-facing outages** since pipeline implementation
- 🧪 Automated test coverage prevents broken builds from reaching production

**Tech Stack:** Python | FastAPI | Docker | GitHub Actions | AWS ECS Fargate | ECR | Application Load Balancer


---

### ☁️ Code-First AWS Cloud Architecture
**Fully modular Terraform repository** for provisioning secure, highly available cloud infrastructure designed specifically for ML workloads.

**Features:**
- Multi-AZ VPC with public/private subnet architecture
- NAT Gateway for secure outbound traffic from private subnets
- OIDC integration for GitHub Actions (no long-lived credentials)
- Modular design: swap components without touching root config

**Why It Matters:** Enables **reproducible environments** across dev/staging/prod. Entire infrastructure can be torn down and rebuilt in minutes, not hours.

---

### 🤖 Over-the-Air (OTA) Edge MLOps
Leveraged mechatronics background to bridge cloud and physical hardware using **AWS IoT Greengrass**.

**The Challenge:** Deploy updated CV inference models to edge devices without manual firmware updates  
**The Solution:** Containerized model artifacts + Greengrass deployment pipelines

**Impact:** Reduced model update cycle from **2 weeks (manual) → 2 hours (automated)**

**Tech Stack:** AWS IoT Greengrass | Docker | Python | PyTorch | Edge Hardware Integration

---

## 💻 Tech Stack

**Cloud & Infrastructure**  
AWS (ECS, Fargate, ECR, VPC, IAM, IoT Greengrass) · Terraform · Linux/Bash

**DevOps & CI/CD**  
Docker · GitHub Actions · Git · DVC (Data Version Control)

**Backend & MLOps**  
Python · FastAPI · Pytest · SQL · CNN · TensorFlow · Keras

**Currently Learning**  
Duke University: *Building Cloud Computing Solutions at Scale* · Shipping [DeepLearning.AI](http://DeepLearning.AI) models to production

---

## 📊 GitHub Activity

<div align="center">

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=Devzane&theme=dark)](https://git.io/streak-stats)

![YOUR_USERNAME's GitHub stats](https://github-readme-stats.vercel.app/api?username=Devzane&show_icons=true&theme=dark&count_private=true&hide=contribs)

</div>

---

## 📫 Let's Build Something

**Open to:** Cloud Engineering · DevOps · MLOps roles at startups shipping AI products  
**Location:** Remote

📧 **Email:** sulaimanabdulmuheez@gmail.com
💼 **LinkedIn:** [linkedin.com/in/abdulmuiz-sulaiman](https://www.linkedin.com/in/abdulmuiz-sulaiman/)  
🌐 **Portfolio:** [yourwebsite.com](https://yourwebsite.com) *(Optional - remove if you don't have one)* 

---

<div align="center">

*"The best infrastructure is the one you never think about—until you need to scale."*

![Profile Views](https://komarev.com/ghpvc/?username=Devzane&color=blue&style=flat-square)

</div>

