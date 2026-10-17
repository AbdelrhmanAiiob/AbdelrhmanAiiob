<img src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:0f172a,50:1d4ed8,100:06b6d4&text=Abdelrhman%20Aiiob&fontColor=ffffff&fontSize=54&fontAlignY=38&desc=Backend%20%26%20Full-Stack%20Engineer&descSize=20&descAlignY=60&animation=fadeIn" width="100%" alt="Abdelrhman Aiiob" />

<div align="center">

[![Typing](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3200&pause=900&color=22D3EE&center=true&vCenter=true&width=720&lines=Python+%2B+Django+in+production;APIs+that+stay+fast+under+real+data;React+%2B+TypeScript+front+ends+that+feel+instant;AI+features+wired+to+real+business+data;I+ship+it%2C+test+it%2C+and+keep+it+running)](https://github.com/AbdelrhmanAiiob)

<a href="mailto:abdelrhmanaliob@gmail.com"><img src="https://img.shields.io/badge/Email-abdelrhmanaliob%40gmail.com-0f172a?style=for-the-badge&logo=gmail&logoColor=22d3ee" alt="Email" /></a>
<a href="mailto:aiiob@icloud.com"><img src="https://img.shields.io/badge/Email-aiiob%40icloud.com-0f172a?style=for-the-badge&logo=icloud&logoColor=22d3ee" alt="Second email" /></a>
<a href="https://www.linkedin.com/in/abdelrhman-aiiob-9379213a9/"><img src="https://img.shields.io/badge/LinkedIn-Abdelrhman%20Aiiob-0f172a?style=for-the-badge&logo=linkedin&logoColor=22d3ee" alt="LinkedIn" /></a>
<img src="https://komarev.com/ghpvc/?username=AbdelrhmanAiiob&style=for-the-badge&color=0f172a&label=PROFILE+VIEWS" alt="Profile views" />

</div>

<br/>

## About me

I build backend systems and the products on top of them. I take a project from the first data model to the Linux server it runs on: the Django API, the database, the React interface, the Nginx and Cloudflare setup, and the tests that keep all of it honest.

- I work **solo end to end** on production projects for real companies and real teams.
- I write **service-layer code with tests**, and I check query counts so a page does not quietly turn into 300 SQL calls.
- I treat **security as part of the build**: login lockout, strict headers and CSP, input hardening, secrets kept out of git.
- I use **AI tools in my workflow** and I also **build AI features**: LLM chat that calls tools over real data, with model and cost control.

<br/>

## Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=py,django,postgres,redis,nginx,linux,docker,cloudflare&perline=8" alt="Backend and infrastructure" />
<br/>
<img src="https://skillicons.dev/icons?i=react,ts,js,tailwind,vite,html,css,playwright&perline=8" alt="Frontend and testing" />
<br/>
<img src="https://skillicons.dev/icons?i=git,github,postman,vscode&perline=8" alt="Tooling" />

</div>

| Area | What I use |
| :-- | :-- |
| **Backend** | Python, Django, Django REST Framework, service layers, background jobs, REST design |
| **Data** | PostgreSQL (tuning, indexes, query audits), Redis caching, SQLite for local work |
| **Frontend** | React, TypeScript, Vite, TanStack Query, Tailwind CSS, Django templates |
| **Infrastructure** | Linux VPS, Nginx reverse proxy, Gunicorn, Cloudflare (DNS, SSL, security), Docker basics |
| **AI** | Gemini and Groq APIs, tool calling, prompt and model design, provider fallback |
| **Quality** | Django test suites, Playwright end-to-end, N+1 audits, security review |

<br/>

## Featured projects

### [RadioNabra](https://radionabra.com): articles and audio streaming platform

> **Role:** Solo backend and infrastructure lead, end-to-end delivery &nbsp;·&nbsp; **Repository:** private, commercial client project

A production platform for publishing cultural articles and streaming podcasts, built for availability, security and an easy back office.

- **Core:** the data layer, business logic and API endpoints in **Python and Django**.
- **Database:** a secured **PostgreSQL** production instance with strict `.env` isolation.
- **Deployment:** **Linux VPS** with **Gunicorn** behind an **Nginx** reverse proxy.
- **Security and uptime:** **Cloudflare** for DNS, SSL termination and traffic filtering, keeping the platform at 99.9% uptime.
- **Back office:** a custom `django-unfold` dashboard so the content team can publish without a developer.
- **Front end:** the backend connected to the template layer, with responsive pages on mobile.

<table>
<tr>
<td width="50%"><img src="assets/radionabra-home.png" alt="RadioNabra home page" /></td>
<td width="50%"><img src="assets/radionabra-search.png" alt="RadioNabra search results" /></td>
</tr>
<tr>
<td align="center"><sub>Home page</sub></td>
<td align="center"><sub>Search results</sub></td>
</tr>
</table>

<br/>

<br/>

### Tonight: AI movie and TV discovery &nbsp;`in progress`

> **Role:** Solo full-stack developer &nbsp;·&nbsp; **Status:** close to release

Helps you decide what to watch tonight, by browsing or by talking to an AI assistant.

- **Data:** the **TMDB** API behind Django endpoints for discovery, search and details, cached in **Redis**.
- **AI chat:** **Groq** and **Gemini** with fallback between providers. It understands what you do not want, supports regenerate, and works in Arabic and English.
- **Learning loop:** every chat turn is logged with provider, latency and regenerate signal, so the prompts improve from real usage.
- **Interface:** **React 19, Vite and Tailwind** with an animated cinematic background, a chat assistant and a details modal.

<table>
<tr>
<td width="50%"><img src="assets/tonight-home.png" alt="Tonight home page" /></td>
<td width="50%"><img src="assets/tonight-chat.png" alt="Tonight AI chat bot recommending movies" /></td>
</tr>
<tr>
<td align="center"><sub>Home page</sub></td>
<td align="center"><sub>Roach, the AI chat bot, recommending movies</sub></td>
</tr>
</table>

<br/>

<br/>

### PlayerHub: order tracking and operations platform

> **Role:** Backend and full-stack developer &nbsp;·&nbsp; **Repository:** private, built for a company

A team uses it every day to follow digital-goods orders from the first message to delivery. Profit, shifts, seller performance and disputes live in one place instead of five spreadsheets and a chat app.

<table>
<tr>
<td width="50%" valign="top">

**Backend**
- Django 6 and DRF on PostgreSQL with Redis caching
- Every write goes through a service layer that records a history entry, and deletes are soft
- Per-order fee and profit breakdown by marketplace
- A 30-minute seller edit window, then manager approval
- Time-tracking sync that starts, pauses and ends shifts automatically
- Encrypted credentials vault

</td>
<td width="50%" valign="top">

**Frontend and AI**
- React 19 and TypeScript with TanStack Query
- Live order board, drawers, voice notes and a chat for each order
- Gemini on Vertex AI with selectable models and thinking levels
- Tool calling over the team's own data, plus a separate assistant for disputes
- Seller dashboards and a monthly Excel report
- Guided rules tour covering ten marketplaces

</td>
</tr>
</table>

```mermaid
flowchart LR
    U[Team in the browser] -->|React 19 + TypeScript| N[Nginx + CSP]
    N --> D[Django + DRF]
    D --> S[Service layer]
    S --> P[(PostgreSQL)]
    S --> R[(Redis)]
    S --> H[History log]
    D --> G[Gemini on Vertex AI]
    D --> T[Time-tracking sync]
    T --> S
```

**Numbers:** 600+ backend tests, 100+ Playwright end-to-end tests, and query-count tests that keep N+1 queries out.

<table>
<tr>
<td width="50%"><img src="assets/playerhub-board.png" alt="PlayerHub order board" /></td>
<td width="50%"><img src="assets/playerhub-dashboard-dark.png" alt="PlayerHub team dashboard in the dark theme" /></td>
</tr>
<tr>
<td align="center"><sub>The live order board</sub></td>
<td align="center"><sub>Team dashboard in the dark theme</sub></td>
</tr>
<tr>
<td colspan="2"><img src="assets/playerhub-assistant-dark.png" alt="PlayerHub AI assistant creating an order" /></td>
</tr>
<tr>
<td colspan="2" align="center"><sub>The AI assistant creating an order from a chat message, with the board updating beside it</sub></td>
</tr>
</table>

<sub>The screenshots use demo data, not real orders, and the assistant answer in the screenshot is a scripted test reply.</sub>

<br/>

## How I work

| | |
| :-- | :-- |
| **Simple first** | The smallest version that works end to end, then layers on top of it. |
| **Tested** | A change is finished when the tests pass, not when it compiles. |
| **Measured** | I look at query counts and bundle sizes before I call something fast. |
| **Safe by default** | Secrets in `.env`, hardened inputs, strict headers, rate limits on login. |
| **Readable** | Code that the next person can follow without asking me. |

<br/>

## Activity

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=AbdelrhmanAiiob&theme=radical&hide_border=true" alt="GitHub streak" />

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:06b6d4,50:1d4ed8,100:0f172a&section=footer" width="100%" alt="" />
