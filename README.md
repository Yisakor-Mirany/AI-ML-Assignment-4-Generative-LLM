# 🧠 AI-ML Assignment 4 — Generative LLM Experimentation

**Student:** Yisakor Mirany  
**Course:** Application Development (AI & Machine Learning)  
**Model Used:** `openai-community/gpt2`  
**Task:** Text Generation (Creative Story Generation)  

---

## 📘 Project Overview

This project demonstrates hands-on experimentation with **Large Language Models (LLMs)** using the **Hugging Face Transformers** library.  
The goal is to explore how changing key generation parameters — such as **temperature**, **top-p (nucleus sampling)**, and **max_new_tokens** — influences the creativity, coherence, and quality of generated text.

We use **GPT-2** (a transformer-based model trained on 40GB of text) to generate creative short stories from a single text prompt and observe how different temperature settings affect the model’s behavior.

---

## ⚙️ Environment Setup

To run the notebook, install the following dependencies:

```bash
pip install torch transformers
