Project Sahadeva — Autonomous Social Reply System

An AI-powered autonomous email reply system built using n8n, Google Gemini, and Gmail API.

Project Sahadeva automatically reads incoming emails, generates intelligent context-aware replies using AI, and creates ready-to-send Gmail drafts — all without manual intervention.

---

🚀 Features

- 📥 Automatic Gmail monitoring using Gmail Trigger
- 🤖 AI-generated email replies powered by Google Gemini
- 🌐 Multilingual support (matches sender's language automatically)
- 🧠 Context memory using LangChain Memory Buffer
- ✍️ Creates Gmail drafts automatically
- ⚡ Fully automated n8n workflow
- 🔎 Real-time information lookup support for dynamic replies
- 👤 Human-like replies without exposing AI identity

---

🛠️ Tech Stack

- "n8n" (https://n8n.io/)
- Google Gemini API
- Gmail API
- LangChain Nodes
- OAuth2 Authentication

---

📂 Workflow Overview

Gmail Trigger
      ↓
AI Agent (Gemini + Memory)
      ↓
Edit Fields
      ↓
Create Gmail Draft

---

🧠 How It Works

1. Gmail Trigger

The workflow continuously monitors your Gmail inbox for new incoming emails.

2. AI Agent

The email subject and content are sent to a Gemini-powered AI agent with custom system instructions.

The AI:

- Understands the email context
- Matches the sender’s language
- Generates a professional human-like response
- Avoids exposing AI-generated behavior
- Can fetch real-time information when necessary

3. Memory Buffer

Conversation memory is maintained using LangChain memory nodes for better contextual understanding.

4. Draft Creation

The generated response is automatically saved as a Gmail draft for review or sending.

---

📸 Example Use Cases

- Personal email assistant
- Customer support automation
- Business inquiry handling
- Smart multilingual communication
- Automated professional responses

---

⚙️ Installation

Prerequisites

- n8n installed
- Google account
- Gemini API access
- Gmail OAuth credentials

---

Setup Steps

1. Clone the Repository

git clone https://github.com/yourusername/project-sahadeva.git
cd project-sahadeva

2. Import Workflow into n8n

- Open n8n
- Go to Workflows
- Click Import from File
- Select the exported workflow JSON

3. Configure Credentials

Set up:

- Gmail OAuth2 credentials
- Google Gemini API credentials

4. Activate Workflow

Enable the workflow to start autonomous email processing.

---

🔐 Security Notes

- Never commit API keys or OAuth credentials
- Use environment variables whenever possible
- Review generated drafts before sending in production environments

---

📌 Future Improvements

- Auto-send replies after approval rules
- Spam detection
- RAG-based personalized memory
- CRM integration
- Slack/Discord/WhatsApp support
- Voice email summarization

---

🤝 Contributing

Contributions are welcome.

Feel free to fork the repository, create feature branches, and submit pull requests.

---

📄 License

MIT License

---

👨‍💻 Author

Sriram Goud Bommagoni

Built with AI, automation, and curiosity 🚀
