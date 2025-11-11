# Calories-Food-Advisor
End To End Large Image Model(LIM) GENAI Using Google Gemini Pro
# 🥗 Health Management App – Calories Food Advisor (Large Image Model GenAI)

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-1.37%2B-FF4B4B?logo=streamlit&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-Integration-success?logo=chainlink&logoColor=white)
![Google Gemini Pro](https://img.shields.io/badge/Google%20Gemini%20Pro-Vision%20Model-orange?logo=google)
![Status](https://img.shields.io/badge/Project_Status-Active-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Platform](https://img.shields.io/badge/Platform-Cloud%20Ready-0078D7?logo=googlecloud)

An **end-to-end Generative AI-powered application** that uses **Google Gemini Pro Vision API** to analyze food images and provide **calorie and nutritional insights**.  
This project leverages **Large Image Models (LIM)**, **LangChain**, and **Streamlit** to deliver an interactive AI experience that combines **computer vision and multimodal reasoning** for real-world health management.

---

## 🚀 Project Overview

The **Calories Food Advisor** is a GenAI-based health management app designed to identify food items from uploaded images and estimate their **total calorie content** using Google’s **Gemini Pro Vision model**.  
The app helps users track their daily calorie intake and promotes **smart dietary habits** through AI-driven insights.

---

## 🧠 Key Features

- 🍎 **AI-Powered Calorie Detection:** Uses Google Gemini Pro Vision (Large Image Model) to recognize food items and estimate calorie intake.  
- 🧩 **Multimodal Reasoning:** Combines visual and text understanding using **LangChain** and **Google Generative AI SDK**.  
- ⚙️ **End-to-End Pipeline:** Covers data ingestion, model inference, response generation, and visualization.  
- 🌐 **Interactive UI:** Built with **Streamlit** for real-time user interaction and instant feedback.  
- ☁️ **Cloud-Ready Architecture:** Designed for deployment on platforms like **Google Cloud**, **AWS**, or **Azure**.  

---

## 🏗️ Tech Stack

| Category | Tools / Libraries |
|-----------|------------------|
| **Frontend / UI** | Streamlit |
| **Backend / APIs** | Google Gemini Pro Vision, Google Generative AI SDK |
| **Orchestration / AI Framework** | LangChain |
| **Embeddings & Vector Store** | FAISS, ChromaDB |
| **Data Processing** | Python, Pillow, PyPDF2, pdf2image |
| **Environment Management** | python-dotenv |
| **Deployment** | Cloud-ready (Google Cloud / Streamlit Cloud) |

---

## 🧩 Architecture Overview

```plaintext
User Uploads Image
        ↓
Streamlit UI
        ↓
Image Preprocessing (Pillow)
        ↓
Google Gemini Pro Vision API (Large Image Model)
        ↓
LangChain Orchestrator (Prompt + Context)
        ↓
Calorie Estimation + Nutritional Summary
        ↓
Streamlit Output Display (User-facing Results)
