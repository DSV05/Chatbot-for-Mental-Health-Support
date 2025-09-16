# Chatbot for Mental Health Support (SDG 3)

## 🧩 Introduction
Mental health issues such as anxiety, stress, and depression are growing concerns, especially among youth. However, access to mental health support is often limited due to social stigma, lack of awareness, and shortage of mental health professionals.  
With advancements in **Artificial Intelligence (AI)** and **Natural Language Processing (NLP)**, there is potential to build intelligent systems that provide basic mental wellness support, encourage self-care, and offer early intervention.

---

## ❗ Problem Statement
Lack of accessible and affordable mental health support among youth often leads to undiagnosed stress, anxiety, and other psychological challenges.  

This project aims to build an **AI-powered chatbot** capable of analyzing users’ emotional and mental state through text inputs and offering supportive, non-judgmental responses along with wellness recommendations.

---

## 🎯 Objective
To develop a **text-based AI chatbot** that detects sentiment and emotional tone of user messages and responds with **empathetic, personalized mental health guidance** using the **Google Gemini API**.

---

## 🌍 Relevance to SDG 3
This project directly contributes to **United Nations Sustainable Development Goal 3 (Good Health and Well-being)** by promoting **mental wellness and emotional self-care**.  
The chatbot facilitates regular mental check-ins and offers early support to help prevent more serious mental health conditions.

---

## ✅ Solution
You can access the working prototype here:  
🔗 [Google Colab Solution](https://colab.research.google.com/drive/1oye6iKDKtvMBq3pS-gr8Vw4x5IuTLPnB?usp=sharing)

---

## 📌 Overview
The solution is an **AI chatbot** that processes user text to detect **emotions** and **sentiment** using machine learning models. It then generates appropriate responses through **Google’s Gemini text generation API**.  

The chatbot currently works via **command-line** or **Google Colab notebook** and can be extended to **mobile or web applications**.

---

## 🚀 Features
- 🔹 Emotion & Sentiment Detection using NLP  
- 🔹 Personalized mental wellness responses  
- 🔹 AI-powered response generation using **Gemini**  
- 🔹 Secure, private, and text-only interaction  
- 🔹 Extensible for journaling, quotes, or mood tracking  

---

## ⚙️ Technical Implementation
1. **Text Input** is analyzed for sentiment using **NLTK VADER**.  
2. **Emotions** are detected using a **HuggingFace transformer model**.  
3. The detected emotional state is passed as context to **Gemini’s text generation model (`text-bison-001`)**.  
4. The chatbot responds with supportive suggestions such as:
   - Breathing exercises  
   - Self-reflection prompts  
   - Positive affirmations  
5. Built entirely in **Python**, deployed in **Google Colab**, and integrated with **Gemini API**.

---

## 🛠 Tools & Technologies
- **Python**  
- **Google Gemini (text-bison-001)**  
- **HuggingFace Transformers**  
- **NLTK (VADER)**  
- **Google Colab**  

---

## 📖 How to Use
1. Open the Colab notebook from the provided link.  
2. Upload your Gemini API key in the notebook.  
3. Run the cells step by step.  
4. Interact with the chatbot via text inputs.  

---

## 📌 Future Scope
- Integration into **mobile/web apps**  
- Support for **voice-based interaction**  
- Advanced **mood tracking & journaling**  
- Personalized **mental wellness routines**  

---

## 🏁 Conclusion
This project demonstrates how **AI can support mental wellness** through a chatbot that detects emotional states and offers **empathetic, context-aware guidance**.  

It promotes **early mental health check-ins**, aligning with **SDG 3: Good Health and Well-being**.  
The solution is scalable, secure, and offers a **non-clinical first step** towards emotional awareness and care.  

---
💡 *Note: This chatbot is not a replacement for professional therapy. For serious mental health concerns, please seek help from licensed professionals.*
