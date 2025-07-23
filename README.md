
# 🧳 TravelMate – Personalized AI-Powered Trip Planner

TravelMate is a full-stack web application that helps users generate **custom travel itineraries** based on their destination, budget, travel duration, and interests. It uses **OpenAI's GPT-4**, the **Google Places API**, and a **React + Python (FastAPI)** stack to provide smart, interactive travel planning at your fingertips.

---

## 🚀 Features

- 🗺️ **Personalized Itinerary Generation** using GPT-4
- 🔍 **Place Recommendations** via Google Places API
- 📆 Select destination, number of days, budget, and interests
- 🧠 Voice input support via Whisper (optional)
- 📄 Download itinerary as PDF or save it for later
- 🖥️ Clean, responsive UI with ReactJS
- ⚡ FastAPI-based backend for scalable performance

---

## 🧠 AI & Tech Stack

| Layer | Technologies |
|-------|--------------|
| Frontend | ReactJS, Tailwind CSS |
| Backend | Python, FastAPI |
| AI | OpenAI GPT-4, Whisper ASR (optional) |
| External APIs | Google Places API, RapidAPI |
| Tools | Git, Postman, Docker (optional), Jupyter |
| Hosting (optional) | Streamlit, Vercel, or Render |

---

## 📸 Screenshots

> (Insert screenshots here: Homepage, Itinerary Output, Voice Input Modal, etc.)

---

## 🛠️ Installation & Usage

### 🔧 Prerequisites
- Python 3.8+
- Node.js (for React)
- OpenAI API Key
- Google Places API Key

### 📦 Backend Setup (FastAPI)
```bash
git clone https://github.com/ojasvi-23/TravelMate
cd TravelMate/backend
pip install -r requirements.txt
uvicorn main:app --reload
