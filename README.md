# 📝 ATS Tracker

A **web-based Applicant Tracking System (ATS) Tracker** that helps users **track job applications efficiently**.  
Built with **Flask** for the backend and a simple **HTML/CSS/JS frontend**. No database is used.  

---

## 🌟 Features

- Add job applications with company name, position, and date  
- Track application status (Applied, Interview, Offer, Rejected)  
- Simple, interactive web interface  
- Lightweight and easy to use  

---

## 🖥 Tech Stack

| Backend | Frontend |
|---------|----------|
| Flask   | HTML, CSS, JS |

---

## 🚀 How It Works

1. User enters job application details in the frontend form.  
2. Frontend sends data to Flask backend.  
3. Backend processes the data (stores in memory while app runs).  
4. Frontend displays the updated list of applications and status.  

**Flow Diagram:**  
User → Frontend JS → Flask Backend → Backend → Frontend → User

Install dependencies:
pip install -r requirements.txt

Create a .env file in the root folder with your API key:
ATS_API_KEY=YOUR_API_KEY_HERE


Run the app:
python main.py


Open your browser at: http://127.0.0.1:8080


🔑 API Key

Required for ATS Tracker to access the external service (e.g., AI or job API).
Store your API key in a .env file:
ATS_API_KEY=YOUR_API_KEY_HERE
Do not push your API key to GitHub for security.

📸 Screenshots / Demo

Dashboard Screenshot:
Demo :
