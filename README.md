# MultiAgent-Clinical-AI-Symptom-Checker
# Multi-Agent Clinical AI Assistant & Symptom Checker 🏥🤖

[![Python 3.10+](https://img.shields.io/badge/python-3.10%2B-blue.svg)](https://www.python.org/)
[![LangChain](https://img.shields.io/badge/Framework-LangChain-green)](https://github.com/langchain-ai/langchain)
[![Vector DB](https://img.shields.io/badge/VectorDB-FAISS-orange)](https://github.com/facebookresearch/faiss)
[![LLM](https://img.shields.io/badge/LLM-Llama_3.3_70B_(Groq)-red)](https://groq.com/)
[![UI](https://img.shields.io/badge/UI-Gradio-ff69b4)](https://github.com/gradio-app/gradio)

An advanced Deep Natural Language Processing (DNLP) system designed to act as a safe, clinically aware medical assistant. This project utilizes a **5-stage multi-agent architecture** orchestrated via LangChain and grounds its clinical insights using a **Retrieval-Augmented Generation (RAG)** pipeline powered by a FAISS vector database.

The assistant processes unstructured, free-text patient symptom descriptions and outputs a structured, safe, and fact-grounded medical report—complete with automated severity assessments and over-the-counter (OTC) guidance.

---

## 🚀 Key Features

* **RAG-Grounded Diagnoses:** Eliminates typical LLM hallucinations by forcing the prediction engine to answer strictly using context retrieved from a verified medical knowledge base.
* **5-Agent Sequential Pipeline:** Features specialized LLM agents (Symptom Extraction, Context Retrieval, Disease Prediction, Medication Guidance, Final Report Compilation) working seamlessly in sequence using structured JSON interfaces.
* **Hybrid Safety Guardrails:** Integrates a deterministic rule-based keyword processor with the LLM to catch medical emergencies instantly, ensuring patient safety comes first.
* **Intuitive UI Dashboard:** A fully interactive web application built with Gradio Blocks featuring color-coded severity banners, example prompts, and tabbed breakdown results.

---

## 🛠️ Tech Stack & Concepts

* **Orchestration Framework:** LangChain (LCEL)
* **Large Language Model:** Llama-3.3-70b-versatile via ChatGroq API
* **Embeddings Model:** `sentence-transformers/all-MiniLM-L6-v2` (384-dimensional dense vectors)
* **Vector Database:** FAISS (Facebook AI Similarity Search)
* **Frontend UI:** Gradio (Multi-tab structure)
* **Core Concepts:** Multi-Agent Architecture, Semantic Search, Prompt Engineering, Structured JSON Outputs, Information Extraction.

---

## 🏗️ System Architecture & Workflow
