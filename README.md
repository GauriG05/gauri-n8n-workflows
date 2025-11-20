# n8n Automation Workflows Collection

This repository contains four automation workflows built using n8n, designed to streamline business operations across content generation, customer support, document processing, and AI-powered knowledge retrieval. Each workflow demonstrates practical applications of LLMs, vector databases, and API integrations.

## Included Workflows

### 1. Invoice Processing Workflow
An automated pipeline that processes invoice PDFs from Google Drive, extracts key fields using LLM-based data extraction, logs the information into Google Sheets, and sends formatted email notifications.
Focus: Document automation, data extraction, email workflows.

### 2. LinkedIn Content Creator
A workflow that reads topics from a Google Sheet, fetches recent insights via web search APIs, generates LinkedIn posts using AI, and updates the sheet automatically.
Focus: Content automation, web search integration, LLM summarization.

### 3. Customer Support Auto-Responder
A complete email automation system that classifies incoming customer messages, retrieves contextual information from a Pinecone vector database, and replies using an AI-powered support agent.
Focus: RAG applications, email handling, automated support.

### 4. RAG Pipeline & Chatbot
An end-to-end Retrieval-Augmented Generation (RAG) pipeline that ingests documents, generates embeddings, stores them in Pinecone, and powers an AI chatbot for question answering.
Focus: Vector search, embeddings, chatbot systems.

## Technologies Used
- n8n
- OpenAI / OpenRouter LLMs
- Pinecone Vector Database
- Google Drive API
- Google Sheets API
- Gmail API

## How to Use
1. Download any workflow JSON file from this repository.
2. Open your n8n dashboard.
3. Click “Import Workflow” and upload the JSON file.
4. Add your API credentials (OpenAI, Google, Pinecone, etc.).
5. Activate the workflow.

## Project Purpose
This repository showcases automation capabilities across multiple domains, demonstrating skills in workflow design, API orchestration, LLM integration, RAG architecture, and data automation. Suitable for employers evaluating AI, automation, or data engineering proficiency.
