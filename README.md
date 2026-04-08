# data-engineering-pipeline-gcp-sales
Pipeline de engenharia de dados utilizando GCP (BigQuery), Python e Looker Studio para análise de vendas.

# 🚀 Pipeline de Engenharia de Dados - Análise de Vendas

## 📌 Sobre o Projeto

Este projeto simula um cenário real de engenharia de dados, onde foi desenvolvido um pipeline completo para ingestão, transformação e análise de dados de vendas.

O objetivo é demonstrar na prática a construção de um fluxo de dados moderno utilizando ferramentas em nuvem.

---

## 🧠 Arquitetura do Projeto
O pipeline foi estruturado em camadas:

* **RAW** → dados brutos armazenados no Google Drive (CSV)
* **TRUSTED** → dados tratados e limpos com Python
* **REFINED** → dados modelados no BigQuery (Data Warehouse)

---

## ⚙️ Tecnologias Utilizadas
* Python (Pandas) → tratamento e transformação de dados
* SQL → consultas e modelagem
* Google BigQuery → Data Warehouse
* Google Drive → armazenamento inicial (RAW)
* Looker Studio → visualização de dados

---

## 🔄 Etapas do Pipeline

### 1. Ingestão de Dados
* Leitura de arquivos CSV armazenados no Google Drive

### 2. Transformação
* Limpeza de dados (nulos, duplicados)
* Padronização de campos
* Normalização dos dados

### 3. Modelagem
* Criação de tabelas fato e dimensão
* Estruturação em modelo dimensional (Star Schema)

### 4. Carga
* Envio dos dados tratados para o BigQuery

### 5. Visualização
* Desenvolvimento de dashboard no Looker Studio
* Análise de vendas por período, produto e cliente

---

## 🧾 Logs
O projeto possui sistema de logs para captura de erros durante execução do pipeline.

---

## ⏰ Automação
Pipeline automatizado via Cloud Scheduler executando diariamente às 05:00.

---

## 📊 Principais Análises
* Evolução das vendas ao longo do tempo
* Ranking de produtos mais vendidos
* Identificação dos principais clientes
* Indicadores de faturamento e ticket médio

---

## 🎯 Objetivo
Demonstrar conhecimentos em engenharia de dados, incluindo:

* Construção de pipelines
* Processos de ETL/ELT
* Modelagem de dados
* Integração com ferramentas de visualização

---

## 📎 Dashboard
🔗 (Em Desenvolvimento, logo subo o link)

---

## 👨‍💻 Autor
Luiz Ricardo de Jesus
Analista de Dados | Engenharia de Dados
