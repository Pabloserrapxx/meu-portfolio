# 🚀 MLOps & AI Engineering Portfolio

Bem-vindo ao meu portfólio de projetos focados em **MLOps**, **Engenharia de Machine Learning** e **LLMs**. Este repositório consolida implementações práticas de pipelines de dados, orquestração de containers e aplicações de Inteligência Artificial Generativa.

## 📂 Projetos

### 1. [Chatbot RAG Local com Docker e Ollama](./03_LLM_RAG_Docker)
**Stack:** Python, LangChain, ChromaDB, FastAPI, Docker, Vanilla JS.

Uma aplicação Full Stack que implementa o padrão RAG (Retrieval-Augmented Generation). O sistema permite conversar com um LLM (TinyLlama) que possui contexto específico injetado dinamicamente.
* **Backend:** API construída com FastAPI para gerenciar a ingestão de documentos e consultas.
* **RAG Service:** Utiliza `LangChain` e `ChromaDB` para indexação vetorial e recuperação de contexto.
* **Infraestrutura:** Orquestração completa via `docker-compose`, integrando a aplicação com o serviço local do Ollama.
* **Frontend:** Interface de chat reativa e moderna.

### 2. [Pipeline de Retreino Automático](./02_Pipeline_Retreino)
**Stack:** Python, Scikit-Learn, Joblib.

Pipeline automatizado para o ciclo de vida de modelos clássicos de Machine Learning. Foca na reprodutibilidade e persistência.
* Implementação de treinamento supervisionado (Random Forest) no dataset Iris.
* Divisão automática de treino/teste e avaliação de métricas (Acurácia).
* Serialização e versionamento de modelos utilizando `joblib` para deploy futuro.

### 3. [Aprendizado Incremental (Online Learning)](./01_Online_Learning)
**Stack:** Python, River.

Demonstração de aprendizado de máquina em fluxo contínuo (streaming), onde o modelo aprende com novos dados em tempo real sem necessidade de retreino total.
* Utiliza a biblioteca `River` para classificação de texto incremental (Naive Bayes Multinomial).
* Loop interativo "Human-in-the-loop" que permite ao usuário corrigir as previsões do modelo, reforçando o aprendizado instantaneamente.

---

## 🛠️ Tecnologias Utilizadas

* **Linguagens:** Python, JavaScript
* **Machine Learning:** Scikit-Learn, River, LangChain
* **Vector Database:** ChromaDB
* **LLM Inference:** Ollama
* **Web/API:** FastAPI
* **DevOps:** Docker, Docker Compose

## 🚀 Como Executar

Cada pasta de projeto contém seu próprio `README.md` com instruções detalhadas. Para o projeto principal de LLM, por exemplo:

```bash
cd 03_LLM_RAG_Docker
docker-compose up --build
# Acesse em http://localhost:8000
