This workflow is an intelligent email auto-responder system built in n8n, using OpenAI GPT models to classify and reply to incoming emails via Gmail. It automates email handling by identifying the intent or category of a message (e.g., order confirmation, promotional, notification, professional, spam, subscription), generating a context-aware response, and replying via the Gmail API.

🚀 Key Features:
Gmail Trigger to receive incoming emails

OpenAI-powered Text Classifier for email categorization

Six parallel LLM branches, each with a tailored response logic

Auto-sends replies using Gmail based on the category

Supports categories like:
🔹 Order Confirmation
🔹 Promotional
🔹 Professional/Work
🔹 Notifications
🔹 Spam/Scam
🔹 Service/Subscription

🧠 Tech Stack:
n8n (Self-hosted)

Gmail API

OpenAI GPT-4 (or GPT-3.5)

Webhook & Automation Logic
