# RAG Demo Workshop 🚀

Hi everyone! We will be building a simple local Retrieval-Augmented Generation (RAG) workflow using LangChain + OpenAI / Azure OpenAI to interact with a PDF book. 🔍📘

## Folder Structure
```
rag-demo/
├── README.md              
├── requirements.txt       
├── pdf/                   
└── src/
    └── rag_workshop.ipynb
```

# Before starting please follow below steps 

## 1. Create & Activate a Virtual Environment
From the project root (`rag-demo/`):
```bash
python3 -m venv .venv
source .venv/bin/activate 
```
To deactivate later:
```bash
deactivate
```

## 2. Install Dependencies
```bash
pip install -r requirements.txt
```
Included packages:
- `langchain`, `langchain-openai`, `langchain-community` — core LangChain + provider integrations
- `faiss-cpu` — vector store backend
- `pypdf` — PDF parsing
- `python-dotenv` — loads environment variables from `.env`
- `requests` — HTTP calls
- `notebook` — Jupyter environment

## 3. Create a `.env` File
In the project root, create a file named `.env`:
```bash
touch .env
```
