<div align="center">

# João Paulo Lomba

### AI Automation Engineer · n8n · LLM Agents · API Integrations

Production AI agents and integration pipelines — built, hardened, and kept running.

[![Portfolio](https://img.shields.io/badge/Portfolio-joaolomba.vercel.app-ff6a00?style=flat-square&logo=vercel&logoColor=white)](https://joaolomba.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-joaolombadev-0A66C2?style=flat-square)](https://www.linkedin.com/in/joaolombadev/)
[![Email](https://img.shields.io/badge/Email-joaolombadev@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:joaolombadev@gmail.com)
[![Location](https://img.shields.io/badge/Bahia,%20Brazil-UTC--3%20·%20Remote-555?style=flat-square)](#)

</div>

---

## About

I build LLM agents and API integration pipelines that run in production, against
real money and real customers. The interesting work is rarely connecting the
APIs — it is containing what the model gets wrong when nobody is watching.

At **Escalys**, I architect and maintain a REST/webhook integration mesh
(Pipefy → n8n → Asaas → WhatsApp) supporting an operation with **11 pipelines and
4 databases**, plus Python AI agents that classify documents and extract
structured data from PDFs.

Independently, I run a WhatsApp ordering agent in production — OpenAI
tool-calling, n8n orchestration, Redis state — handling **~100 real orders every
two days** through a third-party REST API.

Background spans IT support and infrastructure before development, so I own a
workflow end to end: design, integration, failure testing, root-cause analysis
and documentation.

**Open to remote work** — full-time or contract. Registered business entity,
invoices in USD. Professional working proficiency in English.

---

## Featured work

These three read in sequence: **the incident, the pattern it produced, and the
tool that generalises it.**

<table>
<tr>
<td width="33%" valign="top">

### 🔍 [yasmin-whatsapp-ai-agent](https://github.com/joaolombabr/yasmin-whatsapp-ai-agent)

Case study of a production AI ordering agent — the failures that only appear
with real customers, and the deterministic guards that contained them.
Includes the validation node's code.

`n8n` `OpenAI` `REST APIs` `Redis`

</td>
<td width="33%" valign="top">

### 📐 [n8n-production-patterns](https://github.com/joaolombabr/n8n-production-patterns)

Thirteen patterns for running AI agents in n8n against real money, each traced
to a specific incident — including the parts of the n8n execution model that
are not documented anywhere.

`n8n` `AI Agents` `Redis`

</td>
<td width="33%" valign="top">

### 🛡️ [llm-tool-guard](https://github.com/joaolombabr/llm-tool-guard)

FastAPI service that validates an agent's tool call before it becomes an
irreversible action. 44 tests, CI across Python 3.11–3.13, Docker image.

`Python` `FastAPI` `Pytest` `Docker`

</td>
</tr>
</table>

### Engineering highlights

- **Root-caused a silent production failure that had run for months** — an order-status lookup written off as vendor flakiness. One unwired branch, raising no error. Found by auditing connections against expected behaviour, not by guessing.
- **Root-caused an agent emitting invalid product IDs** — the vendor API exposed an undocumented internal field sharing the numeric shape of real IDs. Two prompt-level fixes had already failed; the fix was a deterministic code guard.
- **Reverse-engineered undocumented vendor API behaviour** — combo pricing rules and fee resolution, from response evidence alone.
- **Tested credential and network failures against real endpoints** on an isolated clone, without ever risking live service.

---

## Selected experience

| | |
|---|---|
| **Process Automation & AI Integrations Engineer** — Escalys | Jun 2026 – Present |
| **IT Generalist / Technical Support** — Casa Clínica | 2023 – 2025 |
| **Full Stack & Automation Developer** — Freelance | 2022 – Present |

Technologist in Information Technology Management — UNIAENE-FADBA (2023–2025)
· Databases (Oracle) · Machine Learning (Microsoft)

Client automations built at Escalys — technical-report extraction in Pipefy,
transactional email in n8n — have no public repository. The full case studies
are on the [portfolio](https://joaolomba.vercel.app).

---

## Tech stack

**AI & Automation**

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square)
![Claude](https://img.shields.io/badge/Claude%20API-D97757?style=flat-square&logo=anthropic&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)

**Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Infra & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Frontend**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

---

## Other projects

| Repository | What it is | Stack |
|---|---|---|
| [atend-ia](https://github.com/joaolombabr/atend-ia) | Chatbot with context persistence, built for integration with support channels | FastAPI · Claude API · PostgreSQL · Redis |
| [api-tarefas-spring](https://github.com/joaolombabr/api-tarefas-spring) | REST API with DTOs, validation, filters and global error handling | Java 17 · Spring Boot 3.2 |
| [aws-automation-scripts](https://github.com/joaolombabr/aws-automation-scripts) | Infrastructure automation scripts for AWS | AWS · Bash/PowerShell |

<div align="center">

---

**Looking for someone to build — or fix — an AI automation that touches real money?**

[Let's talk →](mailto:joaolombadev@gmail.com)

</div>
