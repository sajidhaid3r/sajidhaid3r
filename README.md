<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a0b2e,50:4c1d95,100:7c3aed&height=220&section=header&text=MD%20SAJID%20HAIDER&fontSize=48&fontColor=e9d5ff&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%7C%20AI%2FML%20Enthusiast%20%7C%20Full%20Stack%20Developer&descAlignY=58&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=650&lines=Building+at+the+edge+of+AI+%2B+Full+Stack;Turning+ideas+into+production+systems;Pursuing+B.E.+in+Computer+Science;Always+learning%2C+always+shipping" alt="Typing SVG" />

<br/>

[![Bachelor's in Computer Science](https://img.shields.io/badge/B.E.-Computer%20Science-7c3aed?style=for-the-badge&logo=googlescholar&logoColor=white)](#)
[![Location](https://img.shields.io/badge/Location-Bengaluru%2C%20India-4c1d95?style=for-the-badge&logo=googlemaps&logoColor=white)](https://www.google.com/maps/place/Bengaluru,+Karnataka,+India)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-%5BFILL%20IN%20URL%5D-8b5cf6?style=for-the-badge&logo=vercel&logoColor=white)](#)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-md--sajid--haider-6d28d9?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/md-sajid-haider-20869631a)
[![Email](https://img.shields.io/badge/Email-sajidhaid3r%40gmail.com-5b21b6?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sajidhaid3r@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-sajidhaid3r-4c1d95?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sajidhaid3r)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=sajidhaid3r&color=7c3aed&style=for-the-badge&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/sajidhaid3r?color=8b5cf6&style=for-the-badge&label=FOLLOWERS&logo=github)
![Stars](https://img.shields.io/github/stars/sajidhaid3r?color=a78bfa&style=for-the-badge&label=STARS&logo=github)

</div>

<br/>

---

## 🟣 About Me

I'm **MD Sajid Haider**, a Computer Science undergraduate focused on building production-grade software across the AI/ML and full-stack spectrum. My work spans **resilient, edge-native AI platforms**, **realtime full-stack applications**, and **hands-on AI/ML engineering** — including retrieval-augmented generation, LLM API integration, and rapid prototyping with modern frontend tooling.

I approach engineering with a **product mindset**: not just "does it work," but "does it hold up in production, scale cleanly, and solve a real problem end-to-end."

**🎯 Currently open to:**

- Software Engineering Internships / New-Grad Roles
- AI/ML Engineering opportunities
- Full-Stack Development collaborations
- Open Source contributions

<br/>

---

## 🟣 Tech Stack

**Languages**

![Python](https://skillicons.dev/icons?i=python)
![TypeScript](https://skillicons.dev/icons?i=ts)
![JavaScript](https://skillicons.dev/icons?i=js)

**Frontend**

![React](https://skillicons.dev/icons?i=react)
![Vite](https://skillicons.dev/icons?i=vite)
![TailwindCSS](https://skillicons.dev/icons?i=tailwind)
![HTML5](https://skillicons.dev/icons?i=html)
![CSS3](https://skillicons.dev/icons?i=css)

**Backend & Databases**

![Supabase](https://skillicons.dev/icons?i=supabase)
![PostgreSQL](https://skillicons.dev/icons?i=postgres)
![Nodejs](https://skillicons.dev/icons?i=nodejs)

**Cloud, DevOps & Tooling**

![Cloudflare](https://skillicons.dev/icons?i=cloudflare)
![Git](https://skillicons.dev/icons?i=git)
![GitHub](https://skillicons.dev/icons?i=github)
![VSCode](https://skillicons.dev/icons?i=vscode)
![Vercel](https://skillicons.dev/icons?i=vercel)

<br/>

---

## 🟣 AI / ML Expertise

| Domain | Proficiency | Details |
|---|---|---|
| LLM API Integration | Practical | Integrated the Gemini API into applied projects, including handling and comparing raw vs. structured response objects |
| Retrieval-Augmented Generation (RAG) | Practical | Studied and implemented RAG concepts to ground LLM outputs in current/external data and reduce hallucination |
| AI Hallucination Mitigation | Foundational | Explored causes of hallucination in generative models and mitigation strategies (grounding, retrieval, prompt design) |
| Multi-Provider Inference Architecture | Applied | Designed a self-hosted + cloud failover inference layer (AMD MI300X vLLM primary, Groq Cloud fallback) via an OpenAI-compatible API contract |
| Rapid AI Prototyping (Streamlit) | Practical | Built interactive input/output interfaces for LLM-backed tools |
| Applied AI Product Features | Applied | Designed AI chatbot and AI-vision (plastic-type identification) features into a production app architecture |

<br/>

---

## 🟣 Featured Projects

<details open>
<summary><b>🌍 Green Loop — Circular Economy Platform for Plastic Recycling</b></summary>
<br/>

A full-stack platform that turns plastic waste into a circular economy: households schedule pickups, verified collectors complete a **QR-verified handshake**, and both parties earn credits instantly — with manufacturers sourcing verified recycled plastic through a built-in marketplace.

| Category | Details |
|---|---|
| **Stack** | React 18 · TypeScript · Vite 5 (SWC) · Tailwind CSS 3 · shadcn/ui · Radix UI · React Router v6 · TanStack Query v5 · Supabase (Auth, PostgreSQL, Realtime, Edge Functions) · Leaflet + leaflet.heat · Framer Motion |
| **Scale** | 3 user roles (Recycler, Picker, Buyer), 25+ routes, offline-first pickup store synced to Supabase Realtime |
| **Performance** | Instant wallet updates via `postgres_changes` realtime subscriptions — no page refresh on credit/wallet changes |
| **Security** | Atomic QR-verified pickup handshake via Postgres RPC functions (`accept_pickup`, `complete_pickup_transaction`, token-based verification) |
| **Impact** | Live collection heatmaps, CO₂/impact tracking, carbon credit marketplace, community cleanup challenges |
| **Repository** | [github.com/sajidhaid3r/Green-Loop](https://github.com/sajidhaid3r/Green-Loop) |

Green Loop's core engineering challenge was making a two-sided, trust-sensitive handoff (household ↔ collector) both **atomic** and **instant** — solved with a QR-scan-triggered Postgres RPC transaction that updates both wallets in a single call, paired with an in-process event bus so UI state (profile tabs, dashboards, live counters) reacts without polling.

</details>

<br/>

<details open>
<summary><b>⚡ Zero-Gap-AI — Resilient, Edge-Native AI Inference Platform</b></summary>
<br/>

An edge-deployed, TypeScript-first platform built around one core idea: **AI inference should never go down.** Chat/completion requests route through a self-hosted primary inference cluster and transparently fail over to a cloud provider the moment the primary path degrades — closing the gap between a provider outage and a broken user experience.

| Category | Details |
|---|---|
| **Stack** | React 19 · TanStack Start · TanStack Router/Query · Cloudflare Workers · Supabase · Tailwind CSS 4 · shadcn/ui · Zod · React Hook Form |
| **Scale** | Global edge deployment on Cloudflare Workers with near-zero cold starts |
| **Performance** | Requests served from the datacenter closest to the user; edge-first architecture eliminates traditional server latency |
| **Security** | Secrets-driven provider configuration (Wrangler-managed), no hardcoded credentials, strict TypeScript throughout |
| **Impact** | Provider-agnostic failover — primary (AMD MI300X / Llama 3.3 70B via vLLM) to fallback (Groq Cloud) with zero application-code changes |
| **Repository** | [github.com/sajidhaid3r/Zero-Gap-AI](https://github.com/sajidhaid3r/Zero-Gap-AI) |

The defining architectural decision is a **thin, swappable inference abstraction**: both providers speak the OpenAI-compatible chat completions API, so routing logic — not provider-specific glue code — is the actual product surface.

</details>

<br/>

<details open>
<summary><b>🐍 HUSTLE — Applied AI/ML Internship Learning Log</b></summary>
<br/>

A hands-on Python learning repository built during a structured AI internship program, documenting practical work with LLM APIs, hallucination mitigation, RAG, and rapid UI prototyping.

| Category | Details |
|---|---|
| **Stack** | Python · Gemini API · Streamlit |
| **Scale** | Session-based scripts and assignments, iterating from raw API calls to interactive UI-backed tools |
| **Performance** | N/A — learning-focused repository |
| **Security** | N/A — learning-focused repository |
| **Impact** | Foundational applied-AI skills: API integration, hallucination awareness, RAG concepts, Streamlit prototyping |
| **Repository** | [github.com/sajidhaid3r/HUSTLE](https://github.com/sajidhaid3r/HUSTLE) |

Early sessions focused on integrating the Gemini API and comparing raw vs. structured (`response.text`) outputs; later sessions moved into **why LLMs hallucinate** and how **Retrieval-Augmented Generation** grounds model outputs in current data, alongside building a simple Streamlit input/output interface.

</details>

<br/>

---

## 🟣 Experience

**`[FILL IN JOB TITLE]`** · `[FILL IN COMPANY NAME]`
📅 `[FILL IN DATE RANGE]`

`[FILL IN professional description of role and responsibilities]`

- `[FILL IN scope of work bullet]`
- `[FILL IN scope of work bullet]`
- `[FILL IN scope of work bullet]`

`[FILL IN SKILL TAGS]`

<br/>

---

## 🟣 Achievements

<div align="center">

| Recognition | Details |
|---|---|
| `[FILL IN]` | `[FILL IN]` |
| `[FILL IN]` | `[FILL IN]` |

</div>

<br/>

---

## 🟣 Certifications

**AWS**
`[FILL IN CERTIFICATION BADGES/LINKS]`

**Oracle**
`[FILL IN CERTIFICATION BADGES/LINKS]`

**NPTEL**
`[FILL IN CERTIFICATION BADGES/LINKS]`

**Cisco**
`[FILL IN CERTIFICATION BADGES/LINKS]`

<br/>

---

## 🟣 Coding Profiles

<div align="center">

[![LeetCode](https://img.shields.io/badge/LeetCode-%5BFILL%20IN%20HANDLE%5D-4c1d95?style=for-the-badge&logo=leetcode&logoColor=white)](#)
[![GeeksforGeeks](https://img.shields.io/badge/GFG-%5BFILL%20IN%20HANDLE%5D-7c3aed?style=for-the-badge&logo=geeksforgeeks&logoColor=white)](#)
[![HackerRank](https://img.shields.io/badge/HackerRank-%5BFILL%20IN%20HANDLE%5D-6d28d9?style=for-the-badge&logo=hackerrank&logoColor=white)](#)
[![CodeChef](https://img.shields.io/badge/CodeChef-%5BFILL%20IN%20HANDLE%5D-8b5cf6?style=for-the-badge&logo=codechef&logoColor=white)](#)

</div>

<br/>

---

## 🟣 GitHub Analytics

<div align="center">

<img src="https://raw.githubusercontent.com/sajidhaid3r/sajidhaid3r/main/github-metrics.svg" width="90%"/>

<br/>

<img src="https://streak-stats.demolab.com?user=sajidhaid3r&theme=radical&hide_border=true&background=0d0221&stroke=7c3aed&ring=a78bfa&fire=8b5cf6&currStreakLabel=e9d5ff" width="49%"/>
</div>

<br/>

---

## 🟣 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy-three-inky.vercel.app/?username=sajidhaid3r&theme=radical&no-frame=true&no-bg=true&margin-w=8&row=1" />
</div>

<br/>

---

## 🟣 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=sajidhaid3r&theme=react-dark&hide_border=true&bg_color=0d0221&color=a78bfa&line=7c3aed&point=e9d5ff" width="100%"/>

<br/>

</div>

<img src="https://raw.githubusercontent.com/sajidhaid3r/sajidhaid3r/main/github-calendar.svg" width="100%"/>

</div>

<br/>

---

## 🟣 Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/sajidhaid3r/sajidhaid3r/output/github-contribution-grid-snake-dark.svg" width="100%"/>

</div>

> Note: the snake animation requires a one-time GitHub Actions workflow set up on a `sajidhaid3r/sajidhaid3r` profile repo to generate `output/github-contribution-grid-snake-dark.svg`.

<br/>

---

## 🟣 Current Focus

```yaml
learning:
  - Advanced RAG architectures & agentic AI systems
  - Distributed systems fundamentals
  - "[FILL IN]"

building:
  - Green Loop — circular economy platform for plastic recycling
  - Zero-Gap-AI — resilient multi-provider AI inference platform
  - "[FILL IN]"

exploring:
  - Edge computing & serverless inference architectures
  - "[FILL IN]"

open_to:
  - Software Engineering Internships
  - AI/ML Engineering roles
  - Open Source collaboration
```

<br/>

---

## 🟣 Connect

<div align="center">

[![Email](https://img.shields.io/badge/Email-sajidhaid3r%40gmail.com-5b21b6?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sajidhaid3r@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-6d28d9?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/md-sajid-haider-20869631a)
[![GitHub](https://img.shields.io/badge/GitHub-sajidhaid3r-7c3aed?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sajidhaid3r)
[![Portfolio](https://img.shields.io/badge/Portfolio-%5BFILL%20IN%20URL%5D-8b5cf6?style=for-the-badge&logo=vercel&logoColor=white)](#)

</div>

<br/>

---

<div align="center">

<i>"Code is the closest thing we have to turning thought directly into reality."</i>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7c3aed,50:4c1d95,100:1a0b2e&height=120&section=footer" width="100%"/>

</div>
