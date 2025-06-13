# AI Chatbot (GPT-3.5 Powered)

This is a fully functional AI-powered chatbot project built using:

- Python (Flask backend)
- OpenAI GPT-3.5 API
- HTML/JavaScript frontend (clean chat UI)
- Fully deployable on Render (backend) and Netlify (frontend)

---

## 🧩 Project Structure

ai-chatbot-project/
│
├── backend/
│ ├── main.py # Flask backend server
│ ├── config_module.py # Loads .env (OpenAI API Key)
│ ├── requirements.txt # Python dependencies
│ ├── .env # Environment variables (not uploaded to GitHub)
│ └── .gitignore
│
└── frontend/
└── index.html # Simple web chat interface


---

## 🚀 How to Run Locally

### 1️⃣ Backend Setup

- Create a virtual environment:

```bash
python -m venv venv
Activate virtual env:
# Windows:
venv\Scripts\activate
Install dependencies: pip install -r requirements.txt
Create .env file inside backend folder:
OPENAI_API_KEY=your-openai-api-key
Run Flask backend:
python main.py
✅ Flask server will run on http://127.0.0.1:5000

2️⃣ Frontend Setup
Open frontend/index.html in your browser.

Update API URL if necessary when deploying online.

🌐 Deployment Instructions
Backend (Flask API)
Host using Render

Set OPENAI_API_KEY in Render environment variables

Use this start command on Render: gunicorn main:app

Frontend (Web UI)
Host using Netlify

Upload frontend/ folder directly

Update index.html to use your Render backend URL:

javascript
fetch("https://your-render-backend-url/chat", ...)

📦 Tech Stack
Python 3.11

Flask

OpenAI SDK (1.x)

JavaScript (vanilla)

Render.com (Backend Hosting)

Netlify.com (Frontend Hosting)

✨ Live Demo (optional)
After deployment, add your live site link here.

🤝 License
MIT License — Feel free to use, modify, and share.

👨‍💻 Developer
Built by Sushil Kantaria

GitHub: sushilkantaria
