# 🚨 Alert Rider – Hazard Reporting App

**Alert Rider** is a web application that allows users to report hazards, study road signs, and learn safe road practices.  
It integrates **AI (OpenAI API)** to rewrite hazard descriptions clearly and professionally, and can translate hazard reports into South African languages.

🔗 **Live Demo:** [Alert Rider App](https://alerttriderapp.onrender.com/)

---

## **✨ Features**
---

- 🌍 **GPS + Map Detection** – Auto-fills current location using Leaflet & OpenStreetMap.  
- 📝 **Hazard Reports** – Users can submit hazards with location, time, and description.  
- 🤖 **AI Suggestion** – Rewrites hazard descriptions with OpenAI for clarity.  
- 🌐 **Translation** – Translates reports into South African languages (Zulu, Xhosa, Venda, etc.).  
- 🎤 **Voice Input** – Voice-to-text hazard reporting.  
- 🌓 **Dark Mode** – Toggle between light and dark themes.  
- 📚 **Road Sign Study Tool** – Helps users learn and recognize road signs with AI support.  

---

## **🚦 Road Sign Study & Recognition**
---

The app teaches and recognizes road signs, focusing on the most common ones:

- Stop Sign: **0.00%**  
- Speed Hump Sign: **3.71%**  
- Speed Limit Sign: **0.72%**  
- No Entry Sign: **0.02%**  
- Children Warning Sign: **40.81%**  
- Parking Reservation Sign: **0.01%**  
- T Junction Sign: **0.02%**  
- Mini-circle Sign: **0.01%**  
- One Way Sign: **54.61%**  
- Traffic Lights: **0.09%**  

⚠️ **Note:** If AI detection confidence is below **90%**, the system returns:  
🚫 *"No sign detected (confidence < 90%)"*

---

## **📂 Project Structure**
---

AlertTRiderApp/
├── backend/ # Express.js backend
│ ├── server.js # Main backend server
│ ├── package.json # Backend dependencies
├── frontend/ # Frontend static files
│ ├── index.html # Homepage
│ ├── report.html # Hazard report page
│ ├── view.html # View saved reports
│ ├── study.html # Road sign study resources
│ ├── navigation.html # Navigation page
│ ├── script.js # Frontend logic
│ ├── style.css # Stylesheet
└── README.md # Project documentation


---

## **🚀 Setup & Run Locally**
---

### **1. Clone the Repository**
```bash
git clone https://github.com/Defence-Ndzhobela/AlertTRiderApp.git
cd AlertTRiderApp
2. Backend Setup
cd backend
npm install
Create a .env file inside backend/ with:
OPENAI_API_KEY=your_openai_api_key_here
PORT=5000
Run the backend:
node server.js
3. Frontend Setup
The frontend is static. Simply open:
For local development, you can also use Live Server (VS Code extension).

🌐 Deployment

Backend: Render / Railway / Vercel

Remember to set OPENAI_API_KEY in hosting environment variables.

Frontend: Vercel / Netlify / GitHub Pages

Update script.js API calls to point to your deployed backend.

🛠️ Tech Stack

Frontend: HTML, CSS, JavaScript, Leaflet.js

Backend: Node.js, Express.js

AI Integration: OpenAI API

Deployment: Render / Vercel

📌 Notes

❌ Never commit .env files or API keys to GitHub.

💤 Free Render instances may spin down with inactivity (first request may be slow).

🌍 Ensure CORS allows your frontend domain to connect to backend.

👤 Authors

Defence Ndzhobela
📍 Johannesburg, South Africa
📧 ndzhobelad@gmail.com
📞 064 793 9043
Singathwa Ngqula

Nontathu Rica Sikhwebu

Sibonelo Duma

Tshepo Madlenge

Lebohang Ratau
