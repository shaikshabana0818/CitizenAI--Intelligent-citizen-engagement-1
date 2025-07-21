# 🤖 CitizenAI – Intelligent Citizen Engagement Platform

**CitizenAI** is a smart public engagement platform that transforms how governments interact with citizens. Built using **Flask**, **IBM Granite models**, and **Watson NLP**, it enables real-time AI-powered support, sentiment analysis, and actionable civic insights.

---

## 🚀 Quick Start

```bash
# 1. Install dependencies
pip install -r requirements.txt

# 2. Run demo (lightweight, no model loading)
python app_demo.py

# 3. Or run full version with AI model
python app.py

# 4. Access in browser:
http://localhost:5000
# Login: admin / password
```

---

## ✨ Features at a Glance

* 💬 **AI Chat Assistant** — Conversational interface backed by IBM Granite LLMs
* 🧠 **Sentiment Analyzer** — Auto-classifies citizen feedback
* ⚠️ **Civic Issue Reporting** — Submit and track local concerns
* 📊 **Analytics Dashboard** — Real-time charts on engagement trends
* 🔐 **User Login System** — Secure, session-based access
* 📱 **Mobile-Responsive UI** — Optimized for all screen sizes

---

## 🧠 AI Capabilities

CitizenAI is powered by IBM’s open-source **Granite Foundation Models**, using:

* **NLU** for understanding user queries
* **Text Generation** for responses
* **Sentiment Classification** for analyzing feedback

**Runtime**: Optimized with `transformers`, `accelerate`, `bitsandbytes`, and `PyTorch`.

---

## 🧰 Tech Stack

| Layer     | Technology                          |
| --------- | ----------------------------------- |
| Backend   | Python 3.11, Flask                  |
| AI Models | IBM Granite 3B (via Hugging Face)   |
| Frontend  | HTML5, CSS3, Jinja2, Chart.js       |
| Runtime   | PyTorch, Accelerate, BitsAndBytes   |
| DevOps    | Docker, Kubernetes (optional)       |
| Hosting   | Render / Railway / Heroku (planned) |

---

## 📁 Project Structure

```
CitizenAI/
│
├── app.py                   # Full Flask app (AI-powered)
├── app_demo.py              # Lightweight demo app
├── templates/               # HTML templates (Jinja2)
│   ├── index.html
│   ├── about.html
│   ├── chat.html
│   ├── dashboard.html
│   └── login.html
│
├── static/
│   ├── css/styles.css       # Core styling
│   ├── Images/              # Icons & assets
│   └── Favicon/             # App favicon
│
├── models/                  # (Optional) AI model wrappers
├── utils/                   # Helpers for AI, sentiment, etc.
├── docs/                    # Setup, deployment, and API docs
├── requirements.txt         # All dependencies
└── README.md                # You are here
```

---

## ⚙️ Prerequisites

* Python 3.7+
* pip
* Minimum 16GB RAM
* (Recommended) NVIDIA GPU with 8GB+ VRAM for faster inference
* CUDA (for GPU support)
* Internet (for model download on first run)

---

## 🛠️ Installation & Setup

```bash
# Clone the project
git clone https://github.com/AkhileshMalthi/citizen-ai.git
cd citizen-ai

# Set up virtual environment
python -m venv venv
# On Windows:
venv\Scripts\activate
# On Linux/macOS:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Launch the app
python app.py
```

---

## 📊 Dashboard Insights

Available at `/dashboard`, view:

* ✅ Total sentiment breakdown (Positive / Neutral / Negative)
* 📋 Submitted civic concerns
* 📈 Planned: time-based visual trends (Chart.js)

---

## 🧱 Development Milestones

### ✅ Milestone 1: Setup & Architecture

* Project structure and base app built with Flask + IBM Granite

### ✅ Milestone 2: Backend Logic

* Routes: `/`, `/about`, `/chat`, `/dashboard`, `/login`, etc.
* Functions: `ask_question()`, `submit_feedback()`, `report_concern()`

### ✅ Milestone 3: Data Management

* Store chat logs, feedback, concerns (in-memory or extendable)

### ✅ Milestone 4: Frontend UI

* Jinja templates + form integration for feedback/chat/report

### ✅ Milestone 5: Testing & Integration

* Session handling, route testing, error handling

### 🔄 Milestone 6 (Optional): Deployment

* Add PostgreSQL or SQLite
* Add admin/user roles
* Deploy via Docker + Render/Railway

---

## 🔮 Planned Enhancements

* 📊 Time-series charts via Chart.js
* 🗂 Persistent DB (PostgreSQL/SQLite)
* 🌍 Multilingual support (translation APIs)
* 🔐 JWT-based Auth
* 📧 Email alerts for concern reports
* 👥 User roles: admin / citizen / analyst
* 🎨 TailwindCSS-based UI

---

## 📚 Documentation

All documentation lives in the [`docs/`](docs/) folder:

* 📋 [Setup Guide](docs/SETUP.md)
* 🚀 [Deployment Guide](docs/DEPLOYMENT.md)
* 🔧 [API Reference](docs/API_REFERENCE.md)
* 🐛 [Dashboard Fixes](docs/DASHBOARD_FIXES.md)

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgments

* IBM Granite & Hugging Face Transformers
* Flask, PyTorch, and open-source contributors
* CivicTech & SmartGov community

---

**CitizenAI – Empowering Governments with Conversational Intelligence.**

> “Smarter public services begin with smarter conversations.”
