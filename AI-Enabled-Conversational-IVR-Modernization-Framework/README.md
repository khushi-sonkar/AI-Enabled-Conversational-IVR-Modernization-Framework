# 🎙️ Conversational IVR Modernization Framework  
### Transforming Legacy VXML IVR into AI-Powered Omnichannel Conversations

Modern Contact Centers still rely heavily on **legacy VXML (VoiceXML) IVR systems**. These traditional systems are rigid, menu-driven ("Press 1, Press 2…") and lack conversational intelligence.

This project modernizes legacy IVR systems by adding:

- 🤖 Conversational AI (NLU/NLP)  
- 🔄 Seamless switching from **Voice → WhatsApp/SMS/Web Chat**  
- ⚡ Real-time admin monitoring  
- 📡 WebSocket-based event streaming  
- 🗂️ Context management & call tracking  
- 🐳 Full Docker support  

It enables enterprises to transform their IVR without rewriting it from scratch.

## ✨ Key Features

### 🔹 Conversational AI Layer  
- Converts audio transcripts or DTMF into **intents**  
- Mock NLU (ACS/BAP adapter) included  
- Easily replace with Dialogflow, Rasa, Lex, Azure Bot  

### 🔹 Real-Time Interaction Dashboard  
React-based dashboard allows monitoring of:
- Live calls  
- User queries  
- Intents  
- Bot responses  
- Channel transitions  

### 🔹 Omnichannel Switching  
Supports transition from Voice IVR to:  
- WhatsApp  
- SMS  
- Web Chat  

### 🔹 Modern Infrastructure Ready  
- Docker & docker-compose included  
- Works on AWS, Azure, GCP, Render, DigitalOcean  

## 🏗️ System Architecture

Legacy IVR (VXML) → Webhook → Integration Layer → NLU → Context Engine → Channels → Admin UI

## 📂 Project Structure
(Complete structure included in main README)

## 🚀 Getting Started
Instructions for local setup and Docker deployment.

## 📈 Future Scope
- STT/TTS integration  
- Advanced NLU  
- Analytics Dashboard  
- Multi-language Support  

## 📄 License
MIT License
