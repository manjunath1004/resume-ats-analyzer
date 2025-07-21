# 📄 Resume ATS Analyzer

Analyze resumes using an ATS-style scoring system with job eligibility suggestions — built with **React**, **FastAPI**, and **Supabase**.

---

## 🚀 Live Demo

🌐 **Frontend:** [Your Vercel Link Here]  
🧠 **Backend API:** [Your Render/Railway Link Here] *(for testing with Postman or frontend)*

---

## ✨ Features

- ✅ Upload resume (PDF)
- 🧠 Extract name, education, experience, and skills
- 📊 Calculate ATS score based on keyword matching
- 📂 Store resume in Supabase Storage
- 🧠 Suggest job roles based on detected skills
- 💡 Give improvement suggestions
- 🔐 Google Auth (Supabase)
- 📱 Mobile responsive UI

---

## 🛠 Tech Stack

**Frontend:**
- React + Tailwind CSS
- Axios, React Router DOM
- Framer Motion animations

**Backend:**
- FastAPI
- pdfplumber (for PDF parsing)
- Supabase Python SDK
- CORS middleware

**Cloud Services:**
- Supabase (Storage + Auth)
- Vercel (Frontend hosting)
- Render / Railway (API deployment)

---

## 🧑‍💻 Getting Started (Local Setup)
### 🔹 Clone the Repo
```bash
git clone https://github.com/manjunath1004/resume-ats-analyzer.git
cd resume-ats-analyzer
git clone https://github.com/manjunath1004/resume-ats-analyzer.git
cd resume-ats-analyzer
```

Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

Backend Setup
``` bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```
 Future Improvements
 
 Admin dashboard
 Skill-level analysis
 AI-based resume suggestions
 Save user history
 Add support for .docx
