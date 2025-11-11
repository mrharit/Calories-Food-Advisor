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

```

## ⚙️ Installation & Setup
1️⃣ Clone the Repository
bash
Copy code
git clone https://github.com/mrharit/Calories-Food-Advisor

2️⃣ Create and Activate Virtual Environment
bash
Copy code
python -m venv venv
source venv/bin/activate    #  (Linux/Mac)
venv\Scripts\activate       #  (Windows)

3️⃣ Install Dependencies
bash
Copy code
pip install -r requirements.txt

4️⃣ Set Up Environment Variables
Create a .env file in your root directory and add your Google API key:

bash
Copy code
GOOGLE_API_KEY=your_google_api_key_here

5️⃣ Run the Application
bash
Copy code
streamlit run app.py


## 📦 Requirements
Your requirements.txt file should include:

nginx
Copy code
streamlit
google-generativeai
python-dotenv
langchain
PyPDF2
chromadb
pdf2image
faiss-cpu
langchain_google_genai

## 💡 How It Works
Users upload a food image through the Streamlit interface.

The image is processed and sent to Google Gemini Pro Vision (a multimodal LLM) for visual understanding.

Using LangChain, the model is prompted to describe the food items and estimate their calorie content.

The system returns a structured, human-readable nutrition breakdown with calorie estimates per item.

## 📊 Example Output

Input:

🍽️ Image of Rice, Salad, and Chicken

Output:

markdown
Copy code
1. Rice - 200 calories  
2. Grilled Chicken - 250 calories  
3. Green Salad - 80 calories  

✅ Total Calories: 530 kcal

## 🌍 Real-World Use Case
This project addresses a real-world problem by providing a convenient AI-based tool for:

Health & Fitness Tracking

Nutrition Awareness

Smart City & Healthcare Tech Integration

Personalized Diet Planning

## 🧠 Learning & Takeaways
Through this project, I developed strong hands-on experience in:

Generative AI (Google Gemini Pro, LangChain)

Prompt Engineering and Multimodal AI Integration

Streamlit App Development & Deployment

End-to-End ML/AI System Design and Cloud Readiness

## 📈 Future Enhancements

🔍 Integrate OCR for analyzing food labels or menus.

🗣️ Add voice-based interaction using Gemini Speech APIs.

📱 Build mobile-responsive version via Streamlit or React.

🧮 Connect with real-world nutrition databases (e.g., USDA API).

🤝 Contributing
Contributions, feedback, and suggestions are always welcome!
Feel free to open issues or submit pull requests.
