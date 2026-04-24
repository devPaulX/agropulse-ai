# 🌾 AgroPulse AI  
### AI-powered Crop Risk Prediction & Advisory System

AgroPulse AI is an AI-driven agricultural intelligence system that predicts crop risks using weather data and image analysis, and provides real-time, farmer-friendly advisory using Large Language Models.

It is deployed on **Google Cloud Run** and designed for low-tech accessibility via web/API.

---

## 🚀 Live Demo
- Cloud Run API:  
https://agropulse-ai-605474435194.europe-west1.run.app

---

## 🎯 Problem Statement

Farmers face significant crop losses due to:
- Delayed detection of plant diseases
- Unpredictable weather conditions
- Lack of real-time actionable agricultural guidance

Existing solutions are either too complex, inaccessible, or not real-time.

---

## 💡 Solution

AgroPulse AI provides an end-to-end intelligent system that:

- Predicts crop risk using weather conditions
- Detects plant disease from images (ML-based or simulated MVP)
- Generates simple farming advice using AI (LLM-powered)
- Delivers output in a clear, actionable format

---

## 🏗️ System Architecture

User Input (Crop + Location + Image)  
→ Weather API + Image Processing  
→ Risk Engine (Rule-based logic)  
→ AI Advisory Layer (LLM)  
→ Response Generator  
→ API Output (Cloud Run)

---

## 🔄 Data Flow

1. User submits crop and location
2. Weather API fetches environmental conditions
3. Image (if provided) is analyzed for disease detection
4. Risk engine evaluates probability of crop damage
5. LLM generates farmer-friendly advisory
6. Final response is returned via API

---

## ⚙️ Tech Stack

### Backend
- Python
- FastAPI

### AI / ML
- Large Language Models (Gemini / OpenAI)
- Basic CNN / image classification (or mock inference for MVP)

### APIs
- Weather API integration

### Infrastructure
- Google Cloud Run
- Docker
- Cloud Build (CI/CD integration)

---

## ✨ Key Features

- 🌦️ Weather-based crop risk prediction  
- 🌿 Plant disease detection (image-based)  
- 🤖 AI-generated farming advisory  
- 📲 Simple API-based response system  
- ☁️ Cloud deployed and auto-scalable  

---

## 📊 Impact

- Reduces crop loss through early warnings  
- Improves agricultural decision-making  
- Makes AI accessible to non-technical farmers  
- Supports sustainable farming practices  

---

## 🚀 Deployment

Deployed on Google Cloud Run:
https://agropulse-ai-605474435194.europe-west1.run.app


---

## 📁 Project Structure
```
AgroPulse-AI/
│
├── app.py
├── requirements.txt
├── Dockerfile
├── README.md
│
├── backend/
│ ├── risk_engine.py
│ ├── weather_service.py
│ ├── ai_advisor.py
│
└── ml/
├── model.py
```

---

## 🧠 Engineering Decisions & Trade-offs

- Rule-based risk engine used for fast MVP delivery instead of full ML model
- LLM used for advisory to ensure human-like explanations
- Cloud Run chosen for zero-maintenance scalable deployment
- Image model simplified to maintain hackathon time constraints

---

## 🔮 Future Improvements

- Satellite-based crop monitoring
- Real CNN-based disease classification model
- WhatsApp / SMS integration for farmers
- Multi-language voice assistant
- Government agriculture data integration

---

## 👨‍💻 Team

**AInigma**  
Project 2030: MyAI Future Hackathon

---

## 🏁 Summary

AgroPulse AI demonstrates how AI can be used to make agriculture more predictive, accessible, and efficient by combining weather intelligence, computer vision, and generative AI into a single system.

