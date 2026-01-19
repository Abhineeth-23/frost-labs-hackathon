# ❄️ Frost Journal

> **The Goal Tracker that Thinks.** > *An intelligent, GenAI-powered agent that transforms passive tracking into active progress.*

Access at: https://frosty-journal.onrender.com/

## 💡 The Problem
Most habit trackers are just **passive spreadsheets**. They record your failure, but they don't help you fix it. Users suffer from:
1.  **Analysis Paralysis:** "I have a goal, but I don't know where to start."
2.  **Behavioral Blindness:** "I keep failing, but I don't know why."
3.  **Isolation:** Tracking goals feels lonely and mechanical.

## 🚀 The Solution: An Active Agent
**Frost Journal** is not just a tracker; it's an accountability partner. We leverage **Google's Generative AI** to plan, diagnose, and motivate users in real-time.

### 🌟 Key Features

#### 1. The Architect (✨ Powered by Gemini 2.5 Flash)
Stuck on a big goal? Just type the title (e.g., "Learn Python"). The Architect instantly generates **5 actionable, database-stored subtasks** to get you moving immediately.

#### 2. The Doctor (🩺 Powered by Gemini 2.5 Flash)
Failing a streak? The Doctor analyzes your quantitative **Step Logs** and qualitative **Journal Entries** to diagnose the root cause of your inconsistency and prescribe specific behavioral micro-adjustments.

#### 3. Frosty The AI Companion (🤖 Powered by Gemini)
A proactive, context-aware chatbot living in your dashboard. "Frosty" offers:
* **Proactive Motivation:** Pops up with encouragement when you visit the app.
* **Contextual Chat:** Knows your current streak and goals for personalized advice.

#### 4. The Visuals (📊 Powered by Google Charts)
We replaced boring data tables with a **GitHub-style Consistency Heatmap**. This interactive visualization (using the Google Charts Library) allows users to see their momentum build up like ice forming on a window.

#### 5. The Scheduler (📅 Powered by Google Calendar)
Deep-link integration allows users to one-click add goal deadlines directly to their personal **Google Calendar**, ensuring they never miss a target.

---

## 🛠️ Tech Stack

### Frontend
* **HTML5 / Jinja2 Templates**
* **Tailwind CSS** (Custom "Frost" Glassmorphism Design System)
* **Google Charts Library** (JavaScript)

### Backend
* **Python (Flask)**
* **PostgreSQL** (Hosted on Neon Tech)
* **Google Generative AI SDK** (`google-generativeai`)

### Deployment
* **Render Cloud Hosting**

## 💻 Installation & Setup

To run Frost Journal locally:

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/your-username/frost-journal.git](https://github.com/your-username/frost-journal.git)
    cd frost-journal
    ```

2.  **Create a Virtual Environment**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3.  **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Set Environment Variables**
    Create a `.env` file in the root directory:
    ```env
    SECRET_KEY=your_secret_key
    DATABASE_URL=postgresql://user:pass@host/dbname
    GOOGLE_API_KEY=your_gemini_api_key_here
    ```

5.  **Run the App**
    ```bash
    flask run
    ```
    Visit `http://127.0.0.1:5000` in your browser.

---

## 👥 Team: npm uninstall

Built with ❄️ and ☕ for the Hackathon.

* **B Sai Abhineeth** - Student from HITAM
* **Abhinav Govind** - Student from NGIT
* **G. Adithya** - Student from GCET
* **R. Varshith Reddy** - Student from CVRIT

---

*© 2026 Frost Journal. Powered by Google Cloud.*
