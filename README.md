# Data / AI / MLOps Engineering Portfolio

## 🛠️ Technologies
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic_API-191919?style=for-the-badge&logo=anthropic&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

## ✨ Features
- 7 end-to-end projects covering the full Data/MLOps engineering stack
- ETL pipeline with Apache Airflow, Docker, and PostgreSQL
- Conversational AI agent using the Anthropic API with real tool use
- End-to-end ML pipeline: train, version with MLflow, serve with FastAPI, retrain via CI/CD
- AWS cloud deployment (EC2) and infrastructure as code (Terraform)
- Workflow automation with n8n (webhooks, conditional logic, Telegram alerts)
- Real-time metrics dashboard with PostgreSQL, FastAPI, and Grafana

## 🎯 Uses
Progressive portfolio built to demonstrate readiness for a remote Data/AI/MLOps engineering role. Each project adds one new layer to the stack, building from foundational ETL up to cloud infrastructure and AI agents. Intended for recruiters, hiring managers, and engineers evaluating full-stack data engineering capability.

## 🔧 Process
Each project was scoped to introduce exactly one new concept while reusing the previous project's stack. Project 1 set the foundation (Airflow + Docker + PostgreSQL); subsequent projects added AI agents, ML versioning, cloud deployment, IaC, workflow automation, and observability — in that order.

## 💡 Learnings
- End-to-end MLOps: training, experiment tracking, serving, and automated retraining in a single pipeline
- Cloud infrastructure is reproducible only when written as code — Terraform made destroy + recreate trivial
- LLM tool use is the key abstraction that makes agents practical: the model routes to the right data source without hardcoded logic

## ▶️ Running the project
Each project lives in its own repository with its own setup instructions. See the project links in the table below.

| # | Project | Repo |
|---|---------|------|
| 1 | ETL Pipeline — Airflow + Docker + PostgreSQL | [airflow-etl](https://github.com/ElioUcan/airflow-etl) |
| 2 | AI Agent — Anthropic API + FastAPI | [ai-agent](https://github.com/ElioUcan/ai-agent) |
| 3 | Workflow Automation — n8n | [project-3-n8n-workflow](https://github.com/ElioUcan/project-3-n8n-workflow) |
| 4 | ML Pipeline — Train + Version + Serve | [project-4-ml-pipeline](https://github.com/ElioUcan/project-4-ml-pipeline) |
| 5 | AWS Deployment — EC2 + Docker | [AWS-deployment-on-EC2](https://github.com/ElioUcan/AWS-deployment-on-EC2) |
| 6 | Infrastructure as Code — Terraform | [terraform-aws-infra](https://github.com/ElioUcan/terraform-aws-infra) |
| 7 | Metrics Dashboard — PostgreSQL + Grafana | [project-7-pipeline](https://github.com/ElioUcan/project-7-pipeline) |
