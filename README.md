# 🧠 Citizen AI – Intelligent Citizen Engagement Platform

![Deploy Status](https://img.shields.io/badge/Deployed-Online-success?style=flat-square&color=brightgreen)
[🌐 Visit App](https://citizen-ai-sb8l.onrender.com)

Citizen AI is a Generative AI-powered platform built to help citizens interact with government services more efficiently. It includes a smart conversational chatbot, sentiment analysis from feedback, and a real-time dashboard — all powered by IBM Watsonx's Granite LLM and deployed using Flask.

---

## 📌 Features

- 🤖 **Civic Chatbot** using IBM Granite (LLM via Watsonx)
- 💬 Real-time answers to queries like Aadhar, Passport, Schemes, etc.
- 🧠 **Sentiment Analysis** from user feedback using TextBlob
- 📊 **Dashboard** to visualize feedback data and trends
- 🎨 Simple UI with `chat.html`, `feedback.html`, `dashboard.html`

---

## 🛠 Tech Stack

| Layer     | Tools/Tech                         |
|-----------|------------------------------------|
| Backend   | Flask, Python                      |
| Frontend  | HTML, CSS                          |
| AI Model  | IBM Granite 13B Instruct v2 (Watsonx) |
| NLP       | TextBlob (Sentiment Analysis)      |
| Deployment| Render.com                         |

---

## 📂 Folder Structure
citizen-ai/
├── app.py
├── templates/
│ ├── chat.html
│ ├── feedback.html
│ └── dashboard.html
├── static/
│ └── style.css
├── requirements.txt
├── Procfile
├── README.md



---

## ⚙️ How to Run Locally

### 🔧 Prerequisites:
- Python 3.9+
- IBM Cloud account with Watsonx access

### 🚀 Installation:
```bash
git clone https://github.com/abidraza-17/citizen-ai.git
cd citizen-ai
pip install -r requirements.txt

IBM_WATSON_ML_API_KEY=_api_key
IBM_WATSON_ML_URL=https://us-south.ml.cloud.ibm.com
IBM_WATSON_ML_PROJECT_ID=54964ddf-77ab-4c70-8e35-f402829f3e83

▶ Run the App:
bash
Copy code
python app.py
🌐 Deployed App
✅ Live Demo: https://citizen-ai-sb8l.onrender.com

📈 Future Improvements
Multi-language support (Hindi, Telugu, etc.)

Integration with real government APIs (e.g., Passport Seva)

User authentication and feedback history

🤝 Acknowledgments
IBM Watsonx and Granite models

Render.com for deployment

Internship Support Team and Mentors

👤 Author
Mohammad Abid
💼 Generative AI Intern | CSE Student




