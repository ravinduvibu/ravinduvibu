<div align="center">

<!-- HERO BANNER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Ravindu%20Vibuthi&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=ML%20Engineer%20%E2%80%A2%20MLOps%20Architect%20%E2%80%A2%20AI%20Product%20Builder&descAlignY=60&descSize=18&animation=fadeIn" width="100%"/>

<!-- TYPING ANIMATION -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=800&color=A78BFA&center=true&vCenter=true&multiline=true&repeat=true&width=750&height=60&lines=Building+Full-Stack+ML+Systems+%F0%9F%A7%A0;From+Raw+Data+%E2%86%92+Production+Models+%E2%86%92+Live+APIs)](https://git.io/typing-svg)

<br/>

<!-- STATUS BADGES -->
[![University](https://img.shields.io/badge/UCSC-Information%20Technology-7C3AED?style=for-the-badge&logo=graduation-cap&logoColor=white)](https://www.ucsc.cmb.ac.lk/)
[![Experience](https://img.shields.io/badge/Industry-1%2B%20Year%20Experience-10B981?style=for-the-badge&logo=briefcase&logoColor=white)](#)
[![Focus](https://img.shields.io/badge/Focus-MLOps%20%7C%20LLMs%20%7C%20CV-F59E0B?style=for-the-badge&logo=brain&logoColor=white)](#)
[![Open to Work](https://img.shields.io/badge/Status-Open%20to%20Opportunities-EF4444?style=for-the-badge&logo=target&logoColor=white)](#)

</div>

---

## `whoami`

```python
ravindu = {
    "name"       : "Ravindu Vibuthi",
    "role"       : ["ML Engineer", "MLOps Architect", "Full-Stack AI Developer"],
    "university" : "University of Colombo School of Computing (UCSC)",
    "focus"      : ["Computer Vision", "NLP / LLMs", "Tabular ML", "AI Product Dev"],
    "philosophy" : "Ship working ML systems — not just notebooks.",
    "currently"  : "Building end-to-end ML pipelines with full production infrastructure",
}
```

> I don't just train models. I **architect**, **version**, **deploy**, and **monitor** them — end-to-end, from raw data to live production systems backed by real DevOps.

---

## 🏗️ ML System Architecture

> Full-stack ML isn't just a model. Here's how I build the complete system:

```
┌─────────────────────────────────────────────────────────────────────────┐
│                      END-TO-END ML SYSTEM DESIGN                        │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                         │
│  [Raw Data]                                                             │
│      │                                                                  │
│      ▼                                                                  │
│  ┌──────────────┐    ┌──────────────┐    ┌──────────────────────────┐  │
│  │  Data Layer  │───▶│  DVC / Delta │───▶│   Feature Engineering    │  │
│  │  S3 / GCS   │    │  Versioning  │    │   Pipelines (Prefect)    │  │
│  └──────────────┘    └──────────────┘    └──────────────────────────┘  │
│                                                     │                   │
│                                                     ▼                   │
│  ┌──────────────┐    ┌──────────────┐    ┌──────────────────────────┐  │
│  │  Experiment  │◀──▶│   MLflow /   │◀───│   Model Training Loop    │  │
│  │  Tracking   │    │   W&B        │    │   PyTorch / HuggingFace  │  │
│  └──────────────┘    └──────────────┘    └──────────────────────────┘  │
│                                                     │                   │
│                                                     ▼                   │
│  ┌──────────────┐    ┌──────────────┐    ┌──────────────────────────┐  │
│  │  Model Reg.  │───▶│  Docker +    │───▶│   FastAPI / TorchServe  │  │
│  │  MLflow/S3  │    │  Kubernetes  │    │   Model Serving Layer    │  │
│  └──────────────┘    └──────────────┘    └──────────────────────────┘  │
│                                                     │                   │
│                                                     ▼                   │
│  ┌──────────────┐    ┌──────────────┐    ┌──────────────────────────┐  │
│  │  Prometheus  │    │  Grafana     │    │   Drift Detection /      │  │
│  │  + Alerts   │◀───│  Dashboards  │◀───│   Evidently AI           │  │
│  └──────────────┘    └──────────────┘    └──────────────────────────┘  │
│                                                     │                   │
│                                                     ▼                   │
│                            [Next.js Frontend / React UI]                │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## ⚙️ MLOps Stack

<div align="center">

### Experiment Tracking & Model Registry
[![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)](https://mlflow.org/)
[![Weights & Biases](https://img.shields.io/badge/W%26B-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black)](https://wandb.ai/)
[![DVC](https://img.shields.io/badge/DVC-945DD6?style=for-the-badge&logo=dvc&logoColor=white)](https://dvc.org/)

### Data Versioning & Pipelines
[![DVC](https://img.shields.io/badge/Data%20Version%20Control-945DD6?style=for-the-badge&logo=dvc&logoColor=white)](#)
[![Prefect](https://img.shields.io/badge/Prefect-024DFD?style=for-the-badge&logo=prefect&logoColor=white)](#)
[![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apache-airflow&logoColor=white)](#)

### Containerization & Orchestration
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://docker.com/)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)](https://kubernetes.io/)
[![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)](#)

### Model Serving & APIs
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![TorchServe](https://img.shields.io/badge/TorchServe-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](#)
[![Triton](https://img.shields.io/badge/Triton%20Inference-76B900?style=for-the-badge&logo=nvidia&logoColor=white)](#)

### Monitoring & Observability
[![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)](#)
[![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)](#)
[![Evidently AI](https://img.shields.io/badge/Evidently%20AI-FF6B6B?style=for-the-badge&logo=chartdotjs&logoColor=white)](#)

### Cloud Infrastructure
[![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=FF9900)](https://aws.amazon.com/)
[![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)](https://cloud.google.com/)
[![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)](#)

### CI/CD for ML
[![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)](#)
[![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)](#)

</div>

---

## 🧠 ML & AI Core

<div align="center">

### Frameworks & Training
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![XGBoost](https://img.shields.io/badge/XGBoost-189BCC?style=for-the-badge&logo=xgboost&logoColor=white)](#)

### Computer Vision
[![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)](#)
[![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)](#)
[![Torchvision](https://img.shields.io/badge/Torchvision-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](#)

### NLP & LLMs
[![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)](#)
[![OpenAI](https://img.shields.io/badge/OpenAI%20API-412991?style=for-the-badge&logo=openai&logoColor=white)](#)
[![RAG](https://img.shields.io/badge/RAG%20Pipelines-7C3AED?style=for-the-badge&logo=databricks&logoColor=white)](#)
[![PEFT / LoRA](https://img.shields.io/badge/PEFT%20%2F%20LoRA-10B981?style=for-the-badge&logo=huggingface&logoColor=white)](#)

### Data & Vector Storage
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)](#)
[![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white)](#)
[![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=for-the-badge&logo=databricks&logoColor=white)](#)
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](#)

</div>

---

## 🔬 ML Pipeline — How I Build a Full System

```bash
# ── Stage 1: Data Versioning ─────────────────────────────────────────────────
dvc init
dvc add data/raw/
dvc push                          # Remote: S3 / GCS

# ── Stage 2: Experiment Tracking ─────────────────────────────────────────────
mlflow experiments create --name "cv-classifier-v1"
# → params, metrics, artifacts all tracked per run

# ── Stage 3: Model Training ───────────────────────────────────────────────────
python train.py \
  --config configs/resnet50.yaml \
  --track mlflow \
  --epochs 50

# ── Stage 4: Containerize the Model ──────────────────────────────────────────
docker build -t ravindu/ml-api:v1.0 .
docker push ravindu/ml-api:v1.0

# ── Stage 5: Deploy to Kubernetes ────────────────────────────────────────────
kubectl apply -f k8s/deployment.yaml
kubectl apply -f k8s/hpa.yaml          # Horizontal Pod Autoscaler

# ── Stage 6: Monitor in Production ───────────────────────────────────────────
# Prometheus scrapes /metrics from FastAPI
# Grafana dashboard: latency, throughput, prediction drift
# Evidently AI: feature drift alerts → triggers retraining pipeline
```

---

## 🏛️ Full-Stack Architecture

```
┌─────────────────────────────────────────────────────────────────┐
│                     FULL-STACK AI PRODUCT                       │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  FRONTEND          BACKEND              ML LAYER                │
│  ─────────         ─────────            ──────────              │
│  Next.js    ──▶   Node.js / Express ──▶  FastAPI              │
│  React      ──▶   REST / GraphQL    ──▶  PyTorch Model         │
│  Tailwind         Microservices          TorchServe / Triton    │
│  TypeScript       Auth / JWT             Model Registry         │
│                   Rate Limiting          A/B Experiment Layer   │
│                        │                                        │
│                        ▼                                        │
│               PostgreSQL  MongoDB  Redis                        │
│               (Structured)(Docs)  (Cache/Queue)                 │
│                        │                                        │
│                        ▼                                        │
│           AWS (EKS + S3 + ECR) / GCP (GKE + GCS)              │
│                GitHub Actions CI/CD → ArgoCD GitOps             │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

## 💻 Full-Stack Tech

<div align="center">

### Frontend
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](#)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](#)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](#)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](#)

### Backend
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](#)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](#)
[![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)](#)

### Databases
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)](#)
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](#)
[![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)](#)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](#)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=RavinduVibuthi&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=A78BFA&icon_color=A78BFA&text_color=c9d1d9"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=RavinduVibuthi&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=A78BFA&text_color=c9d1d9&langs_count=8"/>

<br/>

[![GitHub Streak](https://streak-stats.demolab.com?user=RavinduVibuthi&theme=tokyonight&hide_border=true&background=0d1117&stroke=A78BFA&ring=A78BFA&fire=F59E0B&currStreakLabel=A78BFA)](https://git.io/streak-stats)

</div>

---

## 🎯 What I'm Currently Studying / Building

```
✅  End-to-end MLOps pipeline  →  DVC + MLflow + Kubernetes + Grafana
✅  LLM Fine-tuning with LoRA  →  HuggingFace PEFT on custom datasets
✅  RAG system with Pinecone   →  LangChain + FastAPI + Next.js frontend
🔨  Model drift monitoring     →  Evidently AI + Prometheus alerts
🔨  Multi-modal CV pipeline    →  YOLO + custom training loop + TorchServe
📚  Studying:                  →  Distributed training, Triton Inference Server
```

---

## 🧩 Core Strengths

| Domain | What I Bring |
|--------|-------------|
| **ML Architecture** | Design full model pipelines from data ingestion → training → versioning → serving |
| **MLOps** | Experiment tracking, model registry, automated retraining, drift monitoring |
| **Data Versioning** | DVC-based reproducible datasets tied to model versions |
| **Containerization** | Docker multi-stage builds optimized for ML inference workloads |
| **Kubernetes** | Deploying scalable model APIs with HPA, rolling updates, and resource limits |
| **CI/CD for ML** | GitHub Actions pipelines that test, build, push Docker images, and trigger K8s deploys |
| **LLMs & RAG** | Building retrieval-augmented generation systems with vector DBs and LangChain |
| **Full-Stack** | Complete AI products — model → FastAPI → Next.js frontend → cloud deployment |
| **Computer Vision** | Classification, detection, segmentation pipelines with PyTorch |

---

## 🚀 Goal

> Build AI systems that are **production-grade, reproducible, and monitored** — not just notebooks that work once.

I think in systems. Every project I build includes data versioning, experiment tracking, containerized deployment, and observability from day one.

---

## 📬 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ravindu%20Vibuthi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ravindu-vibuthi-470137272)
[![Email](https://img.shields.io/badge/Email-ravinduvibuthi2004%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ravinduvibuthi2004@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/RavinduVibuthi)

<br/>

*Open to ML Engineering roles, MLOps positions, AI product collaborations, and research opportunities.*

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" width="100%"/>
</div>
