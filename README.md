# AI-Powered-PDF-Question-Answering-System

A simple RAG (Retrieval-Augmented Generation) system using Deepseek, LangChain, and Streamlit to chat with PDFs and answer complex questions about your local documents.

## Pre-requisites

Install Ollama on your local machine from the official website. And then pull the Deepseek model:

```bash
  ollama pull deepseek-r1:1.5b
```

Install the dependencies using pip:

```bash
  pip install -r requirements.txt
```

## Run

Run the Streamlit app:

```bash
  streamlit run pdf_rag.py
```
