# 🧠 Personal Career Chatbot – Siddhant Sharma

This project is a personalized AI chatbot built using **OpenAI GPT-4o**, **Gradio**, and **Pushover** API. It acts as a virtual representative of **Siddhant Sharma**, capable of answering career-related questions, sharing background information, and encouraging meaningful interactions with users.

The chatbot uses context extracted from Siddhant's **resume** and **LinkedIn profile** to simulate intelligent, engaging, and professional conversation. It also records user interest and unresolved questions through API integrations.

---

## 🚀 Features

- 🤖 **AI Chatbot Powered by GPT-4o**
  - Simulates conversations on behalf of Siddhant Sharma.
  - Responds to questions based on resume and LinkedIn profile.

- 📄 **Document Parsing**
  - Extracts data from a resume PDF using `pypdf`.

- 🔗 **Tool Integration with OpenAI Functions**
  - Records user interest (email, name, notes).
  - Captures unanswered or unknown questions.

- 📲 **Real-Time Notifications**
  - Sends updates using the **Pushover API**.

- 🌐 **Web Interface**
  - Built using `gradio` for an easy-to-use chat UI.

---

## 🛠️ Tech Stack

- Python
- OpenAI GPT-4o (via `openai` Python SDK)
- Gradio
- Pypdf
- Pushover API
- dotenv