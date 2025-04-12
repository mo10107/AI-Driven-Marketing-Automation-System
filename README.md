# Multi-agent Marketing Automation System (NTI Final Project)

## Overview

**Multi-agent  Marketing Automation System** is an advanced AI-powered solution that enhances marketing efficiency through intelligent automation. It prioritizes **fine-tuning with DeepSeek-R1-Distill-Llama-8B for chatbot interactions**, **Vision Transformer (ViT) for real-time image deduplication**, and a **multi-agent system for automating market analysis, content creation, and campaign optimization**.

**Demo:** [Click here](https://drive.google.com/drive/folders/19LoAuPynyMstODpmvrjwcKnzSQMHtea5?usp=drive_link)

---

## Features

### 1. Assistant Chatbot

- Uses **Retrieval-Augmented Generation (RAG)** for real-time, accurate responses to frequently asked questions (FAQs).
- Supports both **English and Arabic**.

### 2. Real-Time Image Deduplication System

- Utilizes **Vision Transformer (ViT)** to detect and eliminate near-duplicate images in real time.
- Enhances media asset management by reducing redundant images.

### 3. Multi-Agent Marketing System

This system automates key marketing tasks through specialized AI agents:

#### 🏆 Market Analysis Agent

- Tracks market trends and competitor activity.
- Automates **report generation** and **email campaign execution**.

#### ✍️ Content Marketing Agent

- Automates the creation of **social media posts** and **blog content**.
- Ensures consistent and engaging brand communication.

#### 📈 Campaign Optimization Agent

- Uses **Agglomerative Clustering** for customer segmentation.
- Optimizes targeted **email campaigns** for higher conversion rates.

#### 📊 Data Analysis Agent

- Performs **data preprocessing** before generating insights.
- Chooses the most appropriate **chart type** to create **interactive dashboards**.
- Helps businesses make data-driven marketing decisions.

---

## Fine-Tuning DeepSeek-R1 for Telecom Chatbots

### 1. Instruction Fine-Tuning

- Transformed a **telecom dataset** into an instruction dataset.
- Fine-tuned **DeepSeek-R1-Distill-Llama-8B** using **QLoRA**.
- Deployed the fine-tuned model on **Hugging Face Hub**.
- Evaluated chatbot performance using **llama-3.3-70B-Instruct**.
- **Hugging Face Model:** [moo100/DeepSeek-R1-telecom-chatbot](https://huggingface.co/moo100/DeepSeek-R1-telecom-chatbot)

### 2. Preference Fine-Tuning

- Created a **preference dataset** with **Phi4**, generating preferred responses via evaluation prompts.
- Fine-tuned **DeepSeek-R1-Telecom-Chatbot** using **Unsloth** and **DPOTrainer**.
- **Hugging Face Model:** [moo100/DeepSeek-R1-telecom-chatbot-v2](https://huggingface.co/moo100/DeepSeek-R1-telecom-chatbot-v2)

---

## Contributors

This project was developed as part of the **NTI Final Project** by a team of AI and marketing automation enthusiasts:

- **Mohamed Abdulaziz**
- **Mahmoud Elwaled**
- **Mariam Mustafa**
- **Amr Abdelatey**
- **Ahmed Ali**

---
