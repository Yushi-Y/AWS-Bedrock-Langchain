# AWS-Bedrock-Langchain

This repository contains LLM apps for blog generation, retrieval-augmented generation (RAG), and multi-step agent workflows using **AWS Bedrock**, **AWS Lambda**, **LangChain**, and **LangGraph**.  
The projects are based on tutorials by [Krish Naik](https://www.youtube.com/@krishnaik06) and content from his Udemy course.

## Project Overview

### 📝 Blog Generation
- Built a serverless blog generation application using AWS Bedrock (LLaMA-2-13B) for LLM-powered text generation and AWS Lambda for backend orchestration. The system uses Amazon API Gateway to expose a public REST API endpoint that accepts blog generation requests from Postman. When a user submits a query, API Gateway triggers a Lambda function, which handles the request, queries the foundation model via Amazon Bedrock, and stores the generated blog context to Amazon S3.


### 📄 PDF Question Answering with RAG
- Developed a **PDF question-answering app** using **AWS Bedrock (Claude)** and **LangChain**, with a **Streamlit front-end** for user interaction.

### 🤖 LLM Agentic Workflow
- Built an **LLM agent workflow** using **LangGraph** to call external tools such as **Wikipedia** and **ArXiv search** during conversational flow.

