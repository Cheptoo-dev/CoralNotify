# 🌊 CoralNotify – The Multilingual AI Notification Agent  

> Deliver smart, multilingual, and verifiable notifications via **SMS & Voice** using **Coral Protocol** and partner technologies.  
> Built for the *Build Agentic Software with Coral* Hackathon 🚀  

---

## ✨ What is CoralNotify?  

**CoralNotify** is a **reusable agent** that organizations and developers can plug into their systems to:  

✅ Rewrite & personalize notifications using **Mistral AI** + **OpenAI**  
✅ Translate into multiple languages automatically 🌍  
✅ Deliver as **SMS** 📩 or **Voice** 🗣 using **ElevenLabs**  
✅ Generate **blockchain-based receipts** with **Crossmint** for trust & compliance 🔐  

No more fragmented APIs — one **agentic assistant** handles it all!  

---

## 🛠️ Tech Stack  

This project integrates the required hackathon technologies:  

- 🌊 **[Coral Protocol](https://coralprotocol.org/)** → Agent registry & orchestration  
- 🧠 **[Mistral AI](https://docs.mistral.ai/)** → Summarization, translation, multilingual text handling  
- 🤖 **[OpenAI](https://platform.openai.com/)** → Personalization, tone adjustment, rewriting  
- 🗣 **[ElevenLabs](https://elevenlabs.io/)** → Natural voice synthesis in multiple languages  
- 🔗 **[Crossmint](https://docs.crossmint.com/)** → Verifiable blockchain receipts for notifications  
- ⚛️ **React + Coral SDK** → Simple demo dashboard  

---

## 🚀 How It Works  

1️⃣ **Input your message** → e.g., `“Meeting with Finance team today at 4pm”`  
2️⃣ **Mistral/OpenAI** → Rewrite, personalize, and translate into preferred language  
3️⃣ **ElevenLabs** → Convert text into natural speech  
4️⃣ **SMS/Voice Delivery** → Send notification as SMS or voice call  
5️⃣ **Crossmint** → Mint a credential proving notification was sent  

---

## 🎥 Demo Flow  

- Judge types message in dashboard UI  
- Agent:  
  - Rewrites & translates text  
  - Generates **voice audio**  
  - Sends SMS (simulated or via provider)  
  - Mints a **Proof of Notification credential**  
- Judge receives SMS + hears voice call + sees blockchain receipt  

---

## 📦 Installation  

```bash
# Clone repo
git clone https://github.com/cheptoo-dev/coralnotify.git
cd coralnotify

# Install dependencies
npm install   # for frontend
pip install -r requirements.txt   # if backend in Python

# Run locally
npm run dev
# CoralNotify

🔮 Future Roadmap

Add WhatsApp & Email channels

Bulk messaging (CSV upload)

Analytics dashboard (success/failure rates)

AI-powered voice conversations (interactive agents)

🏆 Hackathon Highlights

Best Use of Coral → Reusable agent in Coral Registry

Best Use of ElevenLabs → Multilingual, lifelike voice notifications

Best Use of Mistral → Translation & rewriting across languages

Best Use of Crossmint → Blockchain-based proof of notifications

💡 Example Use Cases

🏦 Fintech: Loan repayment reminders

🏥 Healthcare: Appointment confirmations

🎓 EdTech: Class schedule updates in local languages

🚚 Logistics: Delivery notifications with verifiable proof

👩‍💻 Authors

Built with ❤️ by Cheptoo Faith (Techmuse) for the Build Agentic Software with Coral Hackathon.
