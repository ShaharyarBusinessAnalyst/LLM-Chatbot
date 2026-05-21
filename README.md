# 🤖 LLM Chatbot with Gemini Pro

A conversational AI chatbot built with Google Gemini Pro and Streamlit, featuring persistent multi-turn conversation history.

## Overview

This app provides a clean chat interface powered by Google's Gemini Pro model. It maintains full conversation context across turns, enabling coherent multi-turn dialogue without losing prior context.

## Features

- Multi-turn conversation with persistent chat history
- Powered by Google Gemini Pro via the `google-generativeai` SDK
- Clean Streamlit chat UI with role-based message rendering
- Secure API key management via `.env` file

## Tech Stack

- **LLM:** Google Gemini Pro
- **Frontend:** Streamlit
- **API:** Google Generative AI SDK
- **Config:** python-dotenv

## Setup & Run

```bash
# Install dependencies
pip install -r requirements.txt

# Add your API key
echo "GOOGLE_API_KEY=your_key_here" > .env

# Run the app
streamlit run llm_chatbot_using_gemini.py
```

## Project Structure

```
├── llm_chatbot_using_gemini.py   # Main app
├── requirements.txt
└── .env                          # API key (not committed)
```
