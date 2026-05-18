# AI-Workflow-for-Smart-Email-Responses-using-n8n

An AI-powered customer support automation workflow built using n8n and Google Gemini API.

This system uses Retrieval-Augmented Generation (RAG) to answer user queries from document-based knowledge sources. If the AI cannot confidently answer a question, the workflow automatically escalates the query to human officials through email notification.

---

# Features

- RAG-based question answering
- Conversational memory support
- Google Docs knowledge retrieval
- Automated email escalation
- Human-in-the-loop fallback system
- AI-powered response generation
- Context-aware support workflow

---

# Problem Statement

Traditional AI chatbots may generate inaccurate or hallucinated answers when relevant context is unavailable.

This project solves that issue by implementing a fallback escalation mechanism:
- If the AI can answer → respond automatically
- If the AI cannot answer → collect user email and notify support officials

This ensures reliable customer support while maintaining automation efficiency.

---

# Workflow Overview

1. User submits a query
2. AI agent retrieves context from Google Docs
3. Gemini AI generates a contextual response
4. System evaluates whether the query can be answered
5. If unanswered:
   - user email is collected
   - escalation email is sent to officials
6. Human support team responds manually

---

# Architecture

<img width="1326" height="367" alt="_- visual selection" src="https://github.com/user-attachments/assets/0bed4a0b-a3c7-484e-a149-c53282ee31b6" />


---

# Tech Stack

- n8n
- Google Gemini API
- Gmail API
- Google Docs API
- RAG Workflow Design

---

# Demo

## Workflow Screenshot

<img width="1856" height="885" alt="image" src="https://github.com/user-attachments/assets/c025fd03-1ff5-4246-97e5-e6f5b3910a06" />



---

# Future Improvements

- Vector database integration
- Confidence scoring
- Multi-document support
- Retry and error handling
- Admin monitoring dashboard
- Real-time analytics

---

# Key Learning Outcomes

- AI workflow orchestration
- Human-in-the-loop system design
- RAG implementation concepts
- Automation using n8n
- API integration handling
- AI fallback and escalation mechanisms

---

# Author

Krittika S
