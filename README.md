# 🤖 AI Data Analyst Agent

This is a small project I built to learn how AI agents can work with real data. It's a chatbot that can answer questions about sales data and even email the answer if I ask it to.

For example, I can ask *"Which region has the highest profit?"* and it will write its own SQL query, run it on a real database, and reply with the answer — no manual SQL from my side.

---

## 🛠️ Tools I used

- **n8n** — to build the AI agent (no-code automation)
- **PostgreSQL (Supabase)** — where the sales data is stored
- **Google Gemini** — the LLM that understands questions and writes SQL
- **Gmail** — so the agent can send email reports
- **Superstore Sales Dataset** — sample data (9,800 rows)

---

## 🏗️ How it works

I ask a question → the agent decides which tool to use → it either answers in chat, sends an email, or both.

---

## 💬 Example

**Me:** "Which region has the highest profit? Email me this."

**Agent:** Replied in chat and sent this email:

> West: $710,219.68 (Highest)
> East: $669,518.73
> Central: $492,646.91
> South: $389,151.46

---

## 🖼️ Screenshots

![Workflow](Screenshot%202026-08-17%20234212.png)
![Chat Example](Screenshot%202026-08-17%20234303.png)
![Email Report](Screenshot%202026-08-17%20234414.png)

---

## 🚀 What I want to add next

- Chart generation, not just text answers
- Better control over when it sends emails

---

## 👤 About me

I'm Vinayak Tailor, a BCA graduate learning data analytics (Excel, SQL, Power BI). This project was my way of exploring how AI agents fit into that world.

📧 vinayaktailor98@gmail.com
