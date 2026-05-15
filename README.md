# EduNex-Autonomous-AI-Tutor-for-Every-Student-Demo
AI Agent Olympics Hackathon · Milan AI Week 2026
# 🎓 EduNex — Autonomous AI Tutor for Every Student

> **AI Agent Olympics Hackathon · Milan AI Week 2026**
> Solo project by **Harish Nalajala**

![EduNex Banner](https://img.shields.io/badge/EduNex-AI%20Tutor-1D9E75?style=for-the-badge&logo=bookstack&logoColor=white)
![Track](https://img.shields.io/badge/Track-Agentic%20Workflows-7F77DD?style=for-the-badge)
![Powered By](https://img.shields.io/badge/Powered%20By-Anthropic%20Claude-378ADD?style=for-the-badge)
![Gemini](https://img.shields.io/badge/Gemini-Google%20AI%20Studio-1D9E75?style=for-the-badge)

---

## 🚀 Live Demo

👉 **[Try EduNex Live](https://edunex.netlify.app)**

---

## 📌 What is EduNex?

**EduNex** is a fully autonomous AI tutoring agent that delivers personalized, interactive learning to K-12 and college students across **every subject** — from Mathematics and Physics to Literature, Coding, and History.

Unlike static study apps or simple chatbots, EduNex is a **true agentic system** — it plans its teaching approach, detects when a student is confused, adapts its strategy mid-session, and never requires human intervention.

---

## ❌ The Problem

| Problem | Reality |
|---|---|
| Private tutors | Too expensive for most families |
| Classroom teaching | One-size-fits-all, not personalized |
| Study apps | Static — don't adapt to learning gaps |
| After school hours | Zero support when students need it most |

**Millions of students struggle alone. EduNex solves this.**

---

## ✅ Our Solution — The 3-Layer Learning Loop

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│  1. EXPLAIN │ ──▶ │  2. QUIZ    │ ──▶ │  3. SOLVE   │
│             │     │             │     │             │
│  Introduces │     │  Generates  │     │  Step-by-   │
│  concepts   │     │  adaptive   │     │  step walk- │
│  clearly    │     │  questions  │     │  through    │
└─────────────┘     └─────────────┘     └─────────────┘
        ▲                                      │
        └──────── Adapts based on student ─────┘
```

- **Explain** — breaks down any concept in student-friendly language, tailored to their level
- **Quiz** — generates adaptive multiple-choice questions, adjusting difficulty based on responses
- **Solve** — walks through problems step by step, teaching the method, not just the answer

---

## 🛠️ Technology Stack

| Technology | Role |
|---|---|
| **Anthropic Claude** | Deep conversational tutoring, adaptive explanations, confusion detection |
| **Gemini / Google AI Studio** | Multimodal reasoning, document & diagram understanding |
| **Agentic Workflow** | Multi-step session planning, in-session memory, self-adjusting strategy |
| **HTML / CSS / JavaScript** | Frontend single-page application |
| **Netlify** | Demo hosting & deployment |

---

## 🧠 How It Works

```
Student Input
     │
     ▼
┌────────────────────────────────────┐
│         EduNex Agent Core          │
│                                    │
│  Mode Detection (Explain/Quiz/Solve│
│         ↓                          │
│  Subject Context Injection         │
│         ↓                          │
│  Anthropic Claude API Call         │
│         ↓                          │
│  Response Formatting & Delivery    │
└────────────────────────────────────┘
     │
     ▼
Personalized Response → Student
```

1. Student selects a **subject** (Maths, Physics, History, etc.) and a **mode** (Explain / Quiz / Solve)
2. EduNex builds a dynamic system prompt tailored to the subject and mode
3. **Claude API** processes the query with full conversation history for context
4. The agent formats and delivers a structured, personalized response
5. In Quiz mode, interactive answer buttons are generated automatically
6. The agent detects confusion signals and adjusts its teaching strategy

---

## 🎯 Key Features

- 📚 **All subjects** — Mathematics, Physics, Chemistry, Biology, History, Coding, Literature, Economics
- 💡 **Explain mode** — clear concept breakdowns with analogies and examples
- 🧠 **Quiz mode** — interactive multiple-choice questions with instant feedback
- 🔍 **Solve mode** — numbered step-by-step problem walkthroughs
- 🔄 **Adaptive** — adjusts difficulty and tone based on student responses
- 💬 **Conversation memory** — remembers full session context
- 📊 **Live stats** — tracks questions asked, quizzes taken, problems solved
- ⚡ **Zero setup** — works instantly in any browser, no login required

---

## 🏗️ Project Structure

```
edunex/
│
├── edunex-demo.html      # Main single-page application
├── README.md             # This file
└── EduNex_Slides_v2.pdf  # Hackathon presentation slides
```

---

## 🚀 How to Run Locally

No installation required. Just:

```bash
# Clone the repository
git clone https://github.com/yourusername/edunex.git

# Open in browser
cd edunex
open edunex-demo.html
```

Or simply double-click `edunex-demo.html` — it runs entirely in the browser.

---

## 💰 Business Value

| Metric | Value |
|---|---|
| Global tutoring market | $200 Billion+ |
| Availability | 24 hours / 7 days a week |
| Target users | K-12 students, College students |
| Human oversight needed | Zero |
| Cost vs private tutor | Fraction of the cost |

**Who benefits:**
- 🎒 K-12 students needing homework help
- 🎓 College students preparing for exams
- 🏫 Schools and educational institutions
- 💻 EdTech platforms seeking AI tutoring integration
- 👨‍👩‍👧 Families who cannot afford private tutors

---

## 🏆 Hackathon Track

**Track:** Agentic Workflows

> EduNex qualifies under the Agentic Workflows track — the agent plans its own teaching steps, calls the Claude API, manages multi-turn conversation state, adapts its strategy based on student responses, and completes multi-step learning sessions without any human intervention.

---

## 🌟 What Makes EduNex Original

1. **True autonomy** — not a chatbot, a fully agentic tutor that plans and adapts
2. **Dual-model architecture** — Claude's reasoning depth + Gemini's multimodal strengths
3. **Confusion detection** — switches teaching strategy mid-session automatically
4. **Universal coverage** — any subject, any level, in one unified agent

---

## 👤 About the Developer

**Harish Nalajala** — Solo participant, AI Agent Olympics Hackathon, Milan AI Week 2026

---

## 📄 License

This project is open source under the [MIT License](LICENSE).

---

*Built with ❤️ for the AI Agent Olympics Hackathon · Milan AI Week 2026*
