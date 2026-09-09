# Hi, I'm Santhosh 👋

CS @ **UC Irvine** (Vision & Graphics) working across **ML systems, retrieval, and evaluation infrastructure**.

I like building where models meet systems: retrieval pipelines, evaluation harnesses that actually block bad
releases, and the infrastructure that makes a model useful past the demo. My work has ranged from
document-understanding and hybrid retrieval to reinforcement-learning process control and C++ edge inference.

[Portfolio](https://github.com/santhoshuppu4) · [LinkedIn](https://linkedin.com/in/santhosh-uppu-0502762a4) · [Email](mailto:uvvs.santhu@gmail.com)

<a href="https://github.com/santhoshuppu4">
  <img src="https://github-readme-stats.vercel.app/api?username=santhoshuppu4&show_icons=true&hide_border=true&count_private=true" height="150" alt="stats" />
</a>
<a href="https://github.com/santhoshuppu4">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=santhoshuppu4&layout=compact&hide_border=true&langs_count=8" height="150" alt="top languages" />
</a>

## What I'm working on

- 🔬 **Calit2 @ UCI** — physics-adjacent ML for energy systems; GRU forecasting models validated across multi-seed robustness studies rather than single best-case runs
- 🌊 **Water-Energy Nexus Center @ UCI** — reinforcement-learning process control for industrial water treatment, cutting predicted operating cost against a fixed-setpoint baseline
- 🏢 **MSH Global** — cloud-native insurance underwriting platform on Azure: intake → quote → underwriting referral → bind → issue, with rules-driven eligibility and rating
- 📄 **Assay** — hybrid retrieval and LLM evaluation over document corpora, with a CI-blocking quality gate
- 🔥 **Ridgeline** — C++20 edge inference and a multi-tenant Kafka control plane for distributed sensor fleets

## Experience

- **MSH Global Inc.** — *Software Engineer Intern*
  Building a cloud-native insurance workflow platform on React, Node.js, PostgreSQL, and Azure. Owned the
  full submission-to-issuance lifecycle, JWT auth with four-role access control, and CI/CD pipelines
  replacing a manual release process.

- **Calit2 Research Center @ UCI** — *Machine Learning Engineer, Energy Systems*
  Drove seed divergence from **~75% of training runs to 0%** through gradient clipping, orthogonal
  initialization, and learning-rate warmup. Built reproducible experiment tracking across **916 runs and
  55 configurations**, making a 16 GB sweep replayable without external tooling.

- **UCI Water-Energy Nexus Center** — *Machine Learning Research Assistant*
  Designed a PyTorch Soft Actor-Critic controller regulating three flow setpoints over 168-hour horizons,
  cutting predicted operating cost **5%** against a fixed-setpoint baseline while holding weekly production
  within 1%. Benchmarked five model families on 2,889 industrial sensor samples, reaching **R² ≈ 0.90**.

## Projects

- **Assay** — *Retrieval & LLM evaluation*
  Raised retrieval recall@10 from **0.62 to 0.87** by fusing BM25 and dense retrieval with reciprocal rank
  fusion and a cross-encoder reranker. Built a CI-blocking evaluation harness over a 1,200-query golden set
  with an LLM judge calibrated to **κ = 0.79** against 300 human labels.

- **Ridgeline** — *Edge inference & distributed systems*
  C++20 edge inference agent sustaining **38 FPS at 47 ms p99** on Jetson Orin Nano, backed by a
  multi-tenant Kafka and DynamoDB control plane handling **42K events/sec** across a 1,000-device fleet.

- **InsureFlow** — *Insurance workflow platform*
  Dictionary-driven intake for Florida homeowners: ~135 fields defined once, driving validation, a rating
  engine, an underwriting referral engine, and the React form from a single source of truth.

## 🛠 Technical Toolkit

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**ML / AI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat)
![ONNX](https://img.shields.io/badge/ONNX%20Runtime-005CED?style=flat&logo=onnx&logoColor=white)
![PEFT](https://img.shields.io/badge/PEFT%20%2F%20LoRA-8A2BE2?style=flat)

**Backend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat&logo=grpc&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat)

**Systems / Cloud**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

## Beyond the build

Computer vision and graphics 🎨 · systems programming 🧩 · finding good coffee ☕
