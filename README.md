# PowerBI-RAG-Assistant
A Retrieval-Augmented Generation (RAG) system for Microsoft Power BI documentation that combines semantic search with large language models for accurate, context-aware answers.

## Overview
This project implements a Retrieval-Augmented Generation (RAG) system designed to improve access to Microsoft Power BI technical documentation. By combining semantic search over official docs with LLM-based answer generation, the system provides precise, up-to-date, and contextually grounded responses to user queries.

## Features
- Semantic chunking and embedding of Power BI documentation using MPNet
- Efficient similarity search via FAISS vector database
- Heuristic URL reranking tailored to Power BI's documentation structure
- Generation of concise, grounded answers using Llama-2-7B-Chat through the CTransformers API
- Evaluation on exact-title and complex queries demonstrating strong retrieval and answer quality

## Installation

```bash
pip install -r requirements.txt
