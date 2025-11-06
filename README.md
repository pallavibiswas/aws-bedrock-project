# AWS Bedrock GenAI RAG Project

This project implements a Retrieval-Augmented Generation (RAG) system using **Amazon Bedrock**, **Aurora Serverless PostgreSQL**, and **Amazon S3**. 
It provides a working demo of document ingestion, embedding, vector storage, and querying via LLMs.

## 💡 Features

- Document ingestion and chunking (PDFs)
- Text embedding using Titan Embeddings v1.2
- Vector storage in Aurora PostgreSQL
- Knowledge Base creation using Amazon Bedrock
- Query interface via Streamlit App
- Configurable temperature and top_p settings
- Prompt filtering for heavy machinery topics only

## 🛠 Tech Stack

- Python
- Amazon Bedrock (LLM & Embeddings)
- Amazon Aurora Serverless (PostgreSQL)
- Amazon S3 (Document Storage)
- Terraform (Infra Provisioning)
- Streamlit (Web App)
