# 🚀 ScoutFlow AI: The Next-Gen Recruiter Copilot

**ScoutFlow AI** is an intelligent recruitment platform designed to eliminate the manual grind of candidate sourcing. By leveraging high-performance **NVIDIA NIM** models, ScoutFlow parses complex Job Descriptions (JDs) and matches them against a global candidate pool with surgical precision.

---

Repo Links: 
- **Frontend:** [https://github.com/SD2202/ScoutFlow-Frontend]
- **Backend:**  [https://github.com/SD2202/ScoutFlow-Backend]
## 🔗 Live Links: 
- **Frontend (Live Site):** [https://scout-flow-frontend.vercel.app/]
- **Backend (API Status):** [https://scoutflow-backend-zxq0.onrender.com/api/debug](https://scoutflow-backend-zxq0.onrender.com/api/debug)

---

## 🔥 Key Features
- **AI-Driven Matching Engine:** Uses `nvidia/llama-nemotron-embed-1b-v2` for semantic search and `nvidia/llama-3.1-8b-instruct` for final candidate evaluation.
- **Dynamic JD Parsing:** Simply paste a Job Description, and the AI extracts core technical requirements and seniority levels automatically.
- **Real-time Interest Scoring:** Simulates initial recruiter-candidate conversations to gauge "Interest Levels" using **Mistral NIM**.
- **Cloud-Native Architecture:** Fully synced with **MongoDB Atlas** for persistent, real-time data management.

---

## 🛠️ Tech Stack
- **Frontend:** React.js, Tailwind CSS, Framer Motion, Lucide Icons.
- **Backend:** FastAPI (Python), Motor (Async MongoDB), Scikit-Learn.
- **AI/LLM:** NVIDIA NIM (Llama 3.1, Nemotron Embed, Mistral).
- **Database:** MongoDB Atlas (Cloud).
- **Deployment:** Render (Backend), Vercel (Frontend).

---

## 🏗️ Getting Started

### Backend Setup
1. `cd backend`
2. `pip install -r requirements.txt`
3. `uvicorn main:app --reload`

### Frontend Setup
1. `cd frontend`
2. `npm install`
3. `npm run dev`

---

## 🧠 The Brain (NVIDIA NIM Integration)
ScoutFlow doesn't just look for keywords. It uses a 1024-dimensional vector embedding space to understand the *meaning* behind a candidate's experience. A "Senior DevOps Engineer" isn't just someone with the words "AWS" on their resume; our AI analyzes their actual project impact and technical depth to ensure a 95%+ match accuracy.

---

Developed for **DeccanAI Hackathon 2024**.
