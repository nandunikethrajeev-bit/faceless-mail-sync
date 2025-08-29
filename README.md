# 🤖 Email Agent Workflow (n8n + LangChain)

This n8n workflow is a faceless automation setup designed by *Niketh* and branded by *May*. 
It listens for chat messages, processes them with AI, and sends dynamic email replies using Gmail.

---

## 🚀 What It Does
- Triggers when a chat message is received
- Uses GPT-4.1-mini via OpenAI to generate smart responses
- Stores context with a memory buffer for better continuity
- Sends replies through Gmail with dynamic fields (To, Subject, Message)

---

## 🧠 Nodes Used
- Chat Trigger – activates on incoming messages  
- AI Agent – central brain powered by LangChain  
- OpenAI Chat Model – generates responses using GPT-4.1-mini  
- Memory Buffer – keeps chat context alive  
- Gmail Tool – sends emails with AI-generated content

---

## 🛠 Setup Instructions
1. Import the .json file into your n8n dashboard
2. Connect your Gmail account via OAuth2
3. Add your OpenAI API credentials
4. Customize the AI prompts or message formatting if needed
5. Activate the workflow and test it with a chat message

---

## 🎨 Branding Vibes
- Inspired by *Travis Scott’s precision* and *Jurassic World’s chaos* 🦖🔥  
- Built for *faceless creators*, family business ops, and tech remixers  
- Designed to be modular, remixable, and GitHub-ready

---

## 📬 Remix Ideas
- Add Telegram or WhatsApp nodes for multi-channel replies  
- Sync with Google Sheets to log conversations  
- Trigger motivational quotes or pop culture drops in responses

---

