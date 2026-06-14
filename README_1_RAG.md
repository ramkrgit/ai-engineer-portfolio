# ai-engineer-portfolio
# Enterprise RAG Chatbot using Azure OpenAI + Cognitive Search

## 📌 Overview
A production‑grade Retrieval‑Augmented Generation (RAG) chatbot that answers questions using internal documents.  
Built with Azure OpenAI, Cognitive Search, Azure ML, and Azure DevOps.

## 🚀 Features
- Document ingestion + text extraction  
- Embeddings generation using Azure OpenAI  
- Vector search using Azure Cognitive Search  
- RAG pipeline with citations  
- Secure API deployed via Azure ML  
- CI/CD using Azure DevOps  
- Simple web-based chat UI  

## 🏗️ Architecture
(Insert architecture diagram here)

**Key Components**
- Azure Blob Storage  
- Azure Cognitive Search (Vector Index)  
- Azure OpenAI (Embeddings + GPT Model)  
- Azure ML Managed Endpoint  
- Azure DevOps Pipelines  
- Web App (React/Flask/Streamlit)

## 📂 Project Structure

/src
/api
/ui
/pipelines
/utils
/infra
/docs

## 🔧 Setup Instructions
1. Create Azure resources (Blob, Cognitive Search, Azure OpenAI, Azure ML).  
2. Upload documents to Blob Storage.  
3. Run ingestion pipeline to extract text + generate embeddings.  
4. Deploy RAG API to Azure ML.  
5. Connect UI to the API endpoint.  
6. Configure CI/CD in Azure DevOps.

## 🧪 Testing
- Unit tests for ingestion + embedding generation  
- API tests for RAG responses  
- Load tests for concurrency  

## 📊 Demo
(Add screenshots or GIFs)

## 📘 Learn More
- [RAG](ca://s?q=Learn_RAG)
- [Azure OpenAI](ca://s?q=Learn_Azure_OpenAI)
- [Azure Cognitive Search](ca://s?q=Learn_Azure_Cognitive_Search)
