# Maria – Secure Voice Collections Agent | Prompt Engineering Project

This project was built as part of a Prompt Engineering Internship assignment for NurixAI.

**Maria** is a secure, empathetic voice-based collections assistant developed using [VAPI.ai](https://vapi.ai). It leverages a system prompt with GPT-4o Mini and real-time voice interaction to simulate a human collections agent handling overdue payments on behalf of XYZ Bank.

---

## 📌 Project Objective

- Build a conversational AI assistant named **Maria**
- Handle outbound calls to customers with overdue payments
- Verify customer identity securely using **SSN or DOB**
- Share account details **only after identity verification**
- Offer structured payment options
- Speak naturally and empathetically while respecting privacy
- Handle edge cases like third-party callers, identity denial, pressure, and silence

---

## 🛠️ Tech Stack

- **LLM**: GPT-4o Mini (Fast Cluster)
- **Voice Output**: ElevenLabs (Turbo)
- **STT (Speech to Text)**: Deepgram Nova-2
- **Platform**: [VAPI.ai](https://vapi.ai)
- **Tools Used**: VAPI.ai, Clipchamp (for video), MS Word

---

## 🎥 Videos & Links

🔗 **Assistant Demo Link (Live in VAPI)**  
https://vapi.ai?demo=true&shareKey=282a8bbe-0885-47bc-ae27-3b4251f9dc94&assistantId=e2754909-681b-4f04-9cba-d135bd6481a3

📹 **Approach Walkthrough (5-Min Video)**  
https://drive.google.com/file/d/1NXW5BhF9zuJauXUb5eC7bC3CSK1Rpvyg/view?usp=sharing

📹 **Demo Call Recording**  
https://drive.google.com/file/d/1JCHOWEBPpWWoPXHN8FqtEs05IIWBp-xY/view?usp=drive_link

---

## 📄 Submission Files

Please find the attached documents that were submitted as part of this project:

- ✅ `Final_System_Prompt.docx` – Full production-ready system prompt  
- ✅ `Prompt_Engineering_Submission_Documentation.pdf` – Includes approach, iterations, and testing analysis

---

## 🔍 Features Implemented

- ✅ One-strike identity rule (rejects on 1 mismatch)  
- ✅ Anti-leak rules for DOB/SSN guessing  
- ✅ Graceful call exit after repeated pressure  
- ✅ Empathetic, human-like tone (with contractions and pauses)  
- ✅ Silent caller fallback via VAPI Idle Timeout logic  
- ✅ Handles real-world edge cases and emotional responses

---

## 🙋‍♂️ Author

**Ashish Khatri**  
Prompt Engineer | B.Tech CSE (AI & ML)  
[LinkedIn](https://www.linkedin.com/in/ashishkhatri-ai/) | [GitHub](https://github.com/ashishkhatri-ai)
