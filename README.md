# 📬 AI Email Management Agent (n8n)

An AI-powered automation workflow built in **n8n**, using **Gmail**, **OpenAI (GPT-4o)**, and **Google Sheets** to manage, classify, label, summarize, and respond to emails — all without human effort.

---

## 🚀 Features

- 📨 **Gmail Trigger**: Detects new unread emails every 5 minutes.
- 🧠 **AI Classification**: Classifies email as:
  - Promotions
  - Social
  - Personal
  - Sales
  - Recruitment
  - Receipts
  - Miscellaneous
- 🏷️ **Auto-Labeling** in Gmail
- ✍️ **Summarization** using GPT-4o
- 📤 **AI-Powered Replies** (personal and sales-specific logic)
- 📊 **Logs to Google Sheets**: Date, Subject, Summary, Snippet
- 📩 **Draft and Send Emails** using GPT output

---

## 🛠️ Tech Stack

- [n8n](https://n8n.io)
- [OpenAI GPT-4o](https://platform.openai.com/)
- [Google Sheets](https://www.google.com/sheets/about/)
- Gmail API
- LangChain Text Classifier node

---

## 📁 Files

| File Name | Description |
|-----------|-------------|
| `Email_Management.json` | The full exported n8n workflow (ready to import)

---

## 🔧 Setup Instructions

1. Import the `Email_Management.json` into your n8n.
2. Connect your Gmail, OpenAI, and Google Sheets credentials.
3. Add your own label IDs in Gmail for each category.
4. Test by sending emails to the connected inbox.
5. View logs in your Google Sheet and monitor replies.

---

## 🔗 Related Projects

- [n8n Feedback Agent (GitHub Repo)](https://github.com/anil1331/n8n-feedback-agent-AB)

