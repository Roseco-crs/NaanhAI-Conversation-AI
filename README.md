
# NaanhAI 🤖

[![Owner](https://img.shields.io/badge/Owner-Co2fi--crs-blue.svg)](https://github.com/roseco-crs)
[![License](https://img.shields.io/badge/License-Apache%202.0-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-In%20Development-orange.svg)]()

**NaanhAI** (pronounced "nan-ai") is an LLM-powered AI assistant for NLP tasks, focusing on Question-answering, Translation, and summarizing. Indeed, it saves users time on writing prompts for daily translation and summarizing.
Developed and maintained by **Coffi Rodolphe Segbedji)**.

---

## 🌟 Key Features

* **Dynamic Persona Adaptation:** Seamlessly switches between tones and styles based on user-provided parameters.
* **Anti-Hallucination Framework:** Built-in logic to prioritize accuracy over "people-pleasing," ensuring the AI admits when it lacks data.
* **Native Fluency:** Optimized to avoid the "robotic" tropes of standard LLMs, using varied syntax and cultural idioms.
* **Context-Aware Reasoning:** Utilizes chain-of-thought processing to handle complex, multi-step queries.
* **Open Source Core:** Designed to run on high-performance open-source backends like Ollama, vLLM, or llama.cpp.

---

## 🛠 Tech Stack

* **Core Model:** openai/gpt-oss-120b, 
* **Back-end:** Python, LangChain
* **Inference:** LangChain-Groq, Groq
* **Orchestration:** LangChain, LangGraph
* **Front-end** Gradio
* **hosting** HuggingFace

---

## 🚀 Quick Start

### Prerequisites
* Python 3.9+
* Groq API Key

### Installation
```bash
# Clone the repository
git clone [https://github.com/Roseco-crs/NaanhAI-Conversation-AI](https://github.com/Roseco-crs/NaanhAI-Conversation-AI)

# Navigate to the directory
cd NaanhAI-Conversation-AI

# Install dependencies
pip install -r requirements.txt
