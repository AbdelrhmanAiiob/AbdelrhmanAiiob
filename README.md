# Hi there, I'm Abdelrhman Aiiob 👋

**Junior BackEnd / Python & Django Developer**  
Focused on architecting scalable backend systems, designing clean APIs, and managing production environments on Linux. Experienced in end-to-end project delivery using modern AI-assisted engineering workflows.

📫 **Reach me at:** [abdelrhmanaliob@gmail.com](mailto:abdelrhmanaliob@gmail.com) | [LinkedIn](https://www.linkedin.com/in/abdelrhman-aiiob-9379213a9/) | [GitHub](https://github.com/AbdelrhmanAiiob)

---

## 🛠️ Core Tech Stack & Engineering Skills

- **Backend Architecture:** Python, Django, Django REST Framework (DRF), RESTful API Design
- **Database & Caching:** PostgreSQL (Production Tuning), Redis, SQLite (Local Testing), Data Modeling
- **DevOps & Infrastructure:** Linux VPS, Nginx (Reverse Proxy), Gunicorn, Cloudflare (DNS, SSL & Security), Docker basics
- **Frontend:** React, TypeScript, Vite, TanStack Query, Django Template Language (DTL), Bootstrap, Tailwind CSS, Responsive Web Design
- **Testing & Quality:** Django test suites, Playwright end-to-end tests, query-count audits (N+1), security review
- **AI Integration:** Gemini and Groq LLM APIs, tool calling, prompt design
- **Tooling & Workflows:** Git & GitHub, Linux CLI, Postman, AI-Assisted Prototyping & Rapid Development

---

## 🌟 Featured Projects

### 📻 [RadioNabra](https://radionabra.com) — Dynamic Articles & Audio Streaming Platform
> **Role:** Solo Backend & Infrastructure Lead (End-to-End Delivery)  
> **Repository:** 🔒 *Private (Commercial Client Project under NDA)*  
> **Live Platform:** [radionabra.com](https://radionabra.com)

A production-ready digital content platform engineered for publishing cultural articles and streaming podcasts with high availability, security, and administrative efficiency.

#### 🔧 Backend & System Engineering:
- **Core Architecture:** Designed and implemented the complete data layer, business logic, and API endpoints using **Python & Django**.
- **Production Database:** Configured and maintained a secure **PostgreSQL** production instance with strict environment variable isolation (`.env`).
- **Linux & VPS Deployment:** Orchestrated the deployment pipeline on a **Linux VPS**, utilizing **Gunicorn** as the WSGI server and **Nginx** as a high-performance reverse proxy.
- **Security & Availability:** Configured **Cloudflare** for DNS management, SSL termination, and automated traffic filtering to maintain 99.9% platform uptime.
- **Admin Infrastructure:** Customized modern back-office tools (`django-unfold`) to deliver an intuitive content-management dashboard for platform creators.

#### ⚡ Product Delivery & AI-Assisted Prototyping:
- **Frontend Integration:** Connected backend context directly to template layers, handling view rendering, state logic, and mobile responsiveness.
- **Rapid Prototyping:** Leveraged **AI-assisted development tools** to accelerate UI/UX prototyping and frontend scaffolding, enabling solo full-cycle project delivery on schedule.

---

### 📦 PlayerHub — Order Tracking & Operations Platform
> **Role:** Backend & Full-Stack Developer  
> **Repository:** 🔒 *Private (built for a company)*

An internal platform that a small sales team uses every day to track digital-goods orders from first message to delivery, with profit, shifts and disputes handled in one place.

- **Backend:** **Django 6 + DRF** on **PostgreSQL** with **Redis** caching. All writes go through a service layer that records a history entry for every change, and deletes are soft.
- **Frontend:** **React 19 + TypeScript** (Vite, TanStack Query, Tailwind) with a live order board, drawers, voice notes and a per-order chat.
- **AI Assistant:** **Gemini on Vertex AI** with selectable models and thinking levels, tool calling over the team's own data, and a separate assistant for dispute chats.
- **Business logic:** marketplace fee and profit breakdown per order, seller dashboards, a monthly Excel report, a client list, and a 30-minute edit window that needs manager approval afterwards.
- **Integrations:** time-tracking sync that drives automatic shift start, pause and end, and an encrypted credentials vault.
- **Security & Performance:** per-username login lockout, CSP and security headers on **Nginx**, Excel formula-injection protection, and query-count tests that keep N+1 problems out.
- **Quality:** 600+ backend tests and 100+ **Playwright** end-to-end tests.

---

### 🎬 Tonight — AI Movie & TV Discovery *(in progress)*
> **Role:** Solo Full-Stack Developer  
> **Repository:** Local, close to release

A discovery app that helps people decide what to watch tonight, by browsing or by chatting with an AI assistant.

- **Backend:** **Django + DRF** with endpoints for discovery, search, details and AI chat, using the **TMDB** API as the data source and **Redis** caching.
- **AI Chat:** **Groq** and **Gemini** with fallback between providers, understanding of what the user does not want, regenerate support, and Arabic and English handling.
- **Learning loop:** every chat turn is logged (provider, latency, regenerate signal) so the prompts can be improved from real usage.
- **Frontend:** **React 19 + Vite + Tailwind**, with a cinematic animated background, a chat assistant and a details modal.

---

## 📊 Activity & Stats

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=AbdelrhmanAiiob&theme=radical&hide_border=true" alt="Abdelrhman's Streak Stats" />
</p>
