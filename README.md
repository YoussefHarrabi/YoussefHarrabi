
# Hi, I'm Youssef 👋

I'm a **software engineer** based in Tunis, Tunisia, with a Software Engineering degree from **ESPRIT** (2026). I build full stack products, and I work on the part of **LLM systems** that decides whether a feature is allowed near real users: **evaluation harnesses, tenant isolation, and prompt injection defence**. Most of what I know about how models fail I learned by publishing something and letting strangers attack it.

## 🔭 What I'm working on

- **Agentic systems:** LangChain and LangGraph agent loops with tool calling, retrieval over pgvector, and tools that forward each user's own token so an agent can never exceed the permissions of the person asking
- **Evaluation infrastructure:** golden set cases, LLM as judge, and a pass or fail check on every merge, so a prompt change is measured instead of argued about
- **LLM security:** row level security, tool gateways, retrieval quarantine with an injection classifier, output leak filters, and budget ceilings, all measured by ablation rather than asserted
- **Full stack delivery:** ASP.NET Core, FastAPI, Spring Boot and Django behind React, Next.js and Angular, shipped and deployed rather than left on a branch
- **Agentic coding:** daily hands on with Claude Code, GitHub Copilot and Codex, with correctness and design staying mine

## 🔒 Break My Agent

**[Repository](https://github.com/YoussefHarrabi/breakmyagent) · [Live, go try it](https://breakmyagent-lime.vercel.app/)**

An LLM agent with real tools over a real multi tenant database. You are signed in at one company as somebody who is not allowed to see what anybody earns. A fourth company holds the executive payroll, and no login exists for it at all. **Ask the agent what your colleagues earn, then try to make it show you the executives.**

- **Six defence layers**, and a panel that switches each one off so you can watch what changes when it is removed
- **Thirty three cases plus two exemplars, nine categories, on every commit.** Most skip the model entirely and hand the defences what a fully captured model would emit, so a pass means the layer held
- **A section called "What still gets through"**, and it is not short. The injection classifier has a false negative that took one attempt to find. Three defects were found by running the thing rather than testing it, and all three were in the code that checks the layers, not the layers

## 📈 Sniper Entries

**[Live](https://sniper-entries.netlify.app)**

An assistant that runs unattended on scheduled fifteen minute cycles, pairing technical strategies I traded myself for two years with a model that confirms or rejects each setup. It **holds for one human confirmation before it executes**, because a non deterministic model in front of a money moving action needs a gate and not a promise.

## 🛠️ Tech I work with

**Languages:**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat&logo=dotnet&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)

**AI / LLM:**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langgraph&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-D4A27F?style=flat&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat&logo=groq&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat&logo=postgresql&logoColor=white)

**Backend:**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![.NET](https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=flat&logo=dotnet&logoColor=white)
![Spring](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)

**Frontend:**
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

**Databases:**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat&logo=elasticsearch&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

**Dev & infra:**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)

## 📫 Get in touch

- 🌐 [youssefharrabi.netlify.app](https://youssefharrabi.netlify.app/)
- 💼 [linkedin.com/in/youssef-harrabi](https://linkedin.com/in/youssef-harrabi/)
- 📧 youssefharrabi99@gmail.com

Open to remote work and to relocating. English, French, Arabic.
