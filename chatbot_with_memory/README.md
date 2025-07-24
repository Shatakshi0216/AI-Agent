# Chatbot with Memory

This project implements a basic AI chatbot with conversational memory using **Streamlit**, **Langchain**, and **Ollama**. The agent remembers previous messages and responds accordingly.

---

## Features

- Streamlit-based interface
- Context-aware replies using memory
- Powered by a local model (Ollama)
- Modular, simple to extend

---

## How It Works

- User input is taken via Streamlit UI
- Langchain manages conversation and memory
- Ollama runs a local LLM for responses

---

## Folder Contents

```
chatbot_with_memory/
├── app.py           # Main Streamlit app
└── README.md        # Project documentation
```

---

## Deployment

This agent can be deployed using **Streamlit Cloud**:

- Repository structure must include this folder.
- Set the app path to: `chatbot_with_memory/app.py`
- Dependencies should be listed in the root `requirements.txt`

Deploy at: [https://share.streamlit.io](https://share.streamlit.io)

---

## Tech Stack

- [Streamlit](https://streamlit.io/)
- [Langchain](https://www.langchain.com/)
- [Ollama](https://ollama.com/)

---

## Author

**Shatakshi Tiwari**
