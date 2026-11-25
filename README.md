---
title: ShopMate E-Commerce Chatbot
emoji: 🛍️
colorFrom: indigo
colorTo: purple
sdk: gradio
app_file: app.py
pinned: false
---

# ShopMate: E-Commerce Support Chatbot

A domain-specific chatbot for online shopping (products, orders, shipping, returns, payments).
Behavior is driven by a structured system prompt (role, context, scope, guardrails, style).

- **LLM API:** Groq (`openai/gpt-oss-120b`)
- **Temperature:** 0.4, **Max tokens:** 500
- **UI:** Gradio ChatInterface with per-session conversation history
- **Secret required:** `GROQ_API_KEY` (Space settings → Variables and secrets)
