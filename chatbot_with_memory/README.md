# Chatbot with Memory

This project implements a basic AI chatbot with conversational memory using **Streamlit**, **Langchain**, and **Ollama**. The agent retains chat history to generate context-aware responses.

---

## Features

- Conversational UI built with Streamlit
- Memory support using Langchain
- Local language model integration via Ollama
- Simple and modular structure for easy customization

---

## How It Works

- User submits messages through the Streamlit interface.
- Langchain manages the chat flow and memory using a chat history object.
- Ollama runs a local LLM to generate responses based on the current context.

---

## Folder Contents

```
chatbot_with_memory/
├── app.py             # Main Streamlit app
├── README.md          # Project-specific documentation
└── requirements.txt   # Dependencies for this agent
```

---

## Deployment

This project can be deployed using **Streamlit Community Cloud**.

- Ensure your repository includes:
  - `chatbot_with_memory/app.py`
  - `requirements.txt` in the same folder or project root
- Set the app path during deployment to: `chatbot_with_memory/app.py`

Streamlit Cloud: [https://share.streamlit.io](https://share.streamlit.io)

---

## Tech Stack

- [Streamlit](https://streamlit.io/)
- [Langchain](https://www.langchain.com/)
- [Ollama](https://ollama.com/)

---

## Author

**Shatakshi Tiwari**
