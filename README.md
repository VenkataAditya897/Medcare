
# 🩺 MedCare – AI-Powered Personal Healthcare Platform

**MedCare** is an AI-driven healthcare platform that helps users monitor, understand, and improve their health through real-time insights, intelligent recommendations, and a conversational AI assistant. By integrating with Google Fit and using advanced Generative AI, MedCare offers a personalized, always-on health companion.

---

## 🌟 Features

- **🧠 AI Chatbot & Voice Assistant**
  - Get natural, contextual health updates and advice.
  - Ask about steps, heart rate, calories, sleep, and more.

- **📊 Real-Time Health Monitoring**
  - Integrated with Google Fit to track:
    - Steps, distance, and calories burned
    - Heart rate and body temperature
    - Blood pressure and SpO2 levels
    - Nutrition and sleep metrics

- **📁 Medical Report Analysis**
  - Upload scanned medical reports (PDF/images).
  - Uses AI (OCR + NLP) to summarize and highlight key health information.

- **📆 Proactive Health Suggestions**
  - Personalized fitness goals and diet plans.
  - Smart alerts based on health trends and anomalies.

- **🧠 Context-Aware Health Memory**
  - Retains historical data for better, personalized suggestions.
  - Builds a timeline of your health journey.

- **🔁 Multi-Agent AI Architecture**
  - Agents for data fetching, classification, summarization, memory, and more.

---

## 🛠️ Tech Stack

- **Backend:** Node.js, Express, Flask (microservices)
- **AI Platform:** LangChain + ChatGroq / OpenAI GPT
- **APIs:** Google Fit API (OAuth 2.0 authentication)
- **Database:** SQLite (for memory), JSON files for snapshots/history
- **Frontend:** HTML, CSS, JS (SSE for real-time updates)
- **Deployment:** Docker

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/medcare.git
cd medcare


### 2. Install Dependencies
npm install

### 3. Create a .env File
Add your Google Fit API credentials:


CLIENT_ID=your_google_client_id
CLIENT_SECRET=your_google_client_secret
REDIRECT_URI=http://localhost:3000/auth/google/callback

### 4. Run the Server
node server.js

### 5. Open in Browser
http://localhost:3000
