# SoluEduIA
Solução para Educação com Inteligencia Artificial, desenvolvida de ponta a ponta, apresentando  habilidades em Arquitetura, Engenharia e Ciencias de Dados + AI, além de Análises, DevOps, MLOps, FinOps e Gerenciamento Ágil de Projeto de Dados.

# EduAI - Plataforma de Análise de Evasão e Recomendação de Aprendizado Adaptativo

[![CI/CD](https://github.com/seuusername/cogna-eduai/actions/workflows/ci.yml/badge.svg)](https://github.com/seuusername/cogna-eduai/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)

## 📋 Visão Geral

O SoluEduAI é uma plataforma completa de dados para o setor educacional, focada em:

- 🎯 **Predição de Evasão**: Identificação precoce de alunos em risco
- 💡 **Recomendação Personalizada**: Sistema RAG com LLM local
- 📊 **Dashboards Interativos**: Visualizações para tomada de decisão
- 🔄 **ETL/ELT Automatizado**: Pipelines robustos com Airflow e dbt
- 🔐 **Governança de Dados**: Catálogo, qualidade e linhagem

## 🏗️ Arquitetura

![Arquitetura](docs/images/architecture.png)

## 🚀 Tecnologias

| Categoria | Tecnologias |
|-----------|-------------|
| **Orquestração** | Apache Airflow, dbt |
| **Armazenamento** | PostgreSQL (OLTP + Vetorial), MinIO (Data Lake), Neo4j (Grafos) |
| **Processamento** | Apache Spark, Python |
| **ML/IA** | Scikit-learn, XGBoost, PyTorch, LangChain, Sentence-Transformers |
| **APIs** | FastAPI, Docker, Kubernetes |
| **Visualização** | Streamlit, Metabase |
| **Governança** | OpenMetadata, Great Expectations, Apache Ranger |
| **Monitoramento** | Prometheus, Grafana, ELK Stack |
| **Infraestrutura** | Terraform, GitHub Actions |

## 📦 Estrutura do Projeto

SoluEduIA/
├── infrastructure/ # IaC (Terraform, K8s)
├── data-engineering/ # Pipelines de dados (Airflow, dbt)
├── data-science/ # Modelos ML (treinamento, experimentos)
├── rag-system/ # Sistema RAG (embeddings, LLM)
├── api/ # APIs FastAPI
├── frontend/ # Dashboards Streamlit
├── governance/ # Catálogo, qualidade, segurança
├── monitoring/ # Observabilidade
└── docs/ # Documentação
