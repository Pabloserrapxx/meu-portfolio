# 🚀 Portfólio de Engenharia de MLOps & IA

Olá! Sou **Pablo Serra**. Este repositório centraliza minha jornada prática em **MLOps**, **Engenharia de Dados** e **Inteligência Artificial Generativa**.

Aqui você encontrará implementações que vão desde algoritmos de aprendizado em tempo real até arquiteturas completas de nuvem com Infraestrutura como Código (IaC).

---

## 🏆 Projeto em Destaque

### ☁️ [Arquitetura MLOps End-to-End na Oracle Cloud (OCI)](https://github.com/Pabloserrapxx/Projeto_MLOps)
> *Provisionamento de Infraestrutura, Orquestração de Pipelines e Deploy Automatizado.*

Este é um projeto completo de MLOps que implementa uma esteira de produção na **Oracle Cloud Infrastructure (OCI)**. O objetivo foi eliminar o "works on my machine", criando um ambiente auditável e escalável.

* **Infraestrutura como Código (IaC):** Provisionamento de VCNs, Subnets, Compute e Storage utilizando **Terraform**.
* **CI/CD Pipeline:** Deploy automatizado da infraestrutura e aplicações via **GitHub Actions**.
* **Ciclo de Vida de ML:** Rastreamento de experimentos com **MLflow** (backend MySQL + Object Storage) e orquestração de DAGs com **Apache Airflow**.
* **Serving & UI:** API de inferência com **FastAPI** e dashboard interativo com **Streamlit**.

**Tech Stack:** `Terraform` `GitHub Actions` `OCI` `Docker` `MLflow` `Airflow` `FastAPI`

---

## 📂 Outros Projetos

### 🎓 [Assistente Acadêmico Inteligente UnB](https://github.com/unb-Sistemas-de-Machine-learning/Grupo2-ChiquinhoAI)
*Projeto desenvolvido na disciplina de Tópicos Especiais de Engenharia de Software.*
Uma API de consulta acadêmica que utiliza **NLP** e **LLMs** para responder dúvidas de alunos com base em dados da Universidade de Brasília.
* **Busca Semântica:** Utiliza o banco vetorial **Qdrant** para indexar e recuperar informações contextuais.
* **IA Generativa:** Integração com **Google Generative AI (Gemini)** para processar linguagem natural e gerar respostas precisas.
* **Engenharia de Dados:** Web Scraper customizado com **BeautifulSoup** para extrair dados oficiais dos sistemas da UnB.
* **Backend:** API REST construída com **FastAPI** seguindo padrões de arquitetura de software.

### 🤖 [Chatbot RAG Local com Docker e Ollama](https://github.com/Pabloserrapxx/LLMs)
Uma aplicação Full Stack que implementa o padrão **RAG (Retrieval-Augmented Generation)** para interagir com documentos privados usando LLMs locais.
* **Engine:** Utiliza `LangChain` e `ChromaDB` para indexação vetorial e injeção de contexto.
* **LLM Local:** Integração com o modelo `TinyLlama` via **Ollama**, rodando totalmente offline.
* **Arquitetura:** Backend em **FastAPI** e Frontend reativo, tudo conteinerizado via **Docker Compose**.

### 🔄 [Pipeline de Retreino Automático](https://github.com/Pabloserrapxx/Pipeline-de-Re-treino-Autom-tico)
Focado na reprodutibilidade e persistência de modelos clássicos.
* Implementação de pipeline supervisionado (Random Forest) com divisão automática de datasets.
* Serialização de artefatos com `joblib` e padronização de métricas de avaliação.

### 🌊 [Aprendizado Incremental](https://github.com/Pabloserrapxx/modelo_de_autotreinamento)
Demonstração de aprendizado de máquina em fluxo contínuo (streaming data).
* Utiliza a biblioteca **River** para treinar um classificador de texto em tempo real.
* Loop *Human-in-the-loop* que permite corrigir o modelo instantaneamente sem necessidade de retreino total.

---

## 🛠️ Arsenal Tecnológico

| Categoria | Tecnologias |
| :--- | :--- |
| **Linguagens** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![Bash](https://img.shields.io/badge/Shell_Script-4EAA25?style=flat&logo=gnu-bash&logoColor=white) |
| **Cloud & IaC** | ![Oracle](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat&logo=oracle&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) |
| **MLOps & AI** | ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white) ![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apache-airflow&logoColor=white) ![Qdrant](https://img.shields.io/badge/Qdrant-D22D42?style=flat&logo=qdrant&logoColor=white) |
| **Frameworks** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white) |
| **Data & ML** | `Google GenAI` `Scikit-Learn` `BeautifulSoup` `River` `Pandas` |

---

### 📫 Contato

Sinta-se à vontade para explorar os códigos e entrar em contato para discutirmos sobre tecnologia e dados.

[LinkedIn](https://www.linkedin.com/in/pablo-serra-66059b2b0/) • [Email](mailto:pabloserrapx4@gmail.com)
