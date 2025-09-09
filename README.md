🚨 Alert Rider – Hazard Reporting App
Alert Rider is a web application that allows users to report hazards, study road signs, and learn safe road practices. It also integrates AI (OpenAI API) to rewrite hazard descriptions more clearly and professionally, and can translate hazard reports into South African languages.
🔗 Live Demo: https://alerttriderapp.onrender.com/
✨ Features
•	🌍 GPS + Map Detection – Auto-fills current location using Leaflet & OpenStreetMap.
•	📝 Hazard Reports – Users can submit hazards with location, time, and description.
•	🤖 AI Suggestion – Rewrites hazard descriptions with OpenAI for clarity.
•	🌐 Translation – Translates reports into multiple South African languages (Zulu, Xhosa, Venda, etc.).
•	🎤 Voice Input – Allows voice-to-text description entry.
•	🌓 Dark Mode – Toggle between light and dark themes.
•	📚 Road Sign Study Tool – Helps users learn and recognize road signs with AI assistance.
🚦 Road Sign Study & Recognition
The app can also teach you road signs by focusing on the most common and important ones:
•	Stop Sign: 0.00%
•	Speed Hump Sign: 3.71%
•	Speed Limit Sign: 0.72%
•	No Entry Road Sign: 0.02%
•	Children Warning Sign: 40.81%
•	Parking Reservation Sign: 0.01%
•	T Junction Sign: 0.02%
•	Mini-circle Road Sign: 0.01%
•	One Way Sign: 54.61%
•	Traffic Lights: 0.09%
⚠️ Note: If AI detection confidence is below 90%, it will return: 🚫 No sign detected (confidence < 90%).
📂 Project Structure
AlertTRiderApp/
├── backend/              # Express.js backend
│   ├── server.js         # Main backend server
│   ├── package.json      # Backend dependencies
├── frontend/             # Frontend static files
│   ├── index.html        # Homepage
│   ├── report.html       # Hazard report page
│   ├── view.html         # View saved reports
│   ├── study.html        # Study road signs/resources
│   ├── navigation.html   # Navigation page
│   ├── script.js         # Frontend logic
│   ├── style.css         # Stylesheet
└── README.md             # Project documentation

🚀 Setup & Run Locally
1. Clone the repo:
git clone https://github.com/Defence-Ndzhobela/AlertTRiderApp.git
cd AlertTRiderApp
2. Backend Setup:
cd backend
npm install

Create a .env file inside backend/ with:
OPENAI_API_KEY=your_openai_api_key_here
PORT=5000

Start the backend:
npm start

Server will run at: http://localhost:5000
3. Frontend Setup:
The frontend is static – just open frontend/index.html in your browser. For local development, you can also serve it using Live Server (VS Code extension).
🌐 Deployment
Backend: Can be deployed on Render, Railway, or Vercel. Remember to set OPENAI_API_KEY in hosting environment variables.
Frontend: Deploy static files (frontend/) to Vercel, Netlify, or GitHub Pages. Update script.js API calls to point to your deployed backend.
🛠️ Tech Stack
•	Frontend: HTML, CSS, JavaScript, Leaflet.js
•	Backend: Node.js, Express.js
•	AI Integration: OpenAI API
•	Deployment: Render / Vercel
📌 Notes
•	Do not commit .env files to GitHub. Keep API keys secret.
•	Free Render instances may spin down with inactivity (first request may be slow).
•	CORS must allow your frontend domain to call the backend.
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
