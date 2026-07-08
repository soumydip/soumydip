# Hi there, I'm Soumyadip Maity! 👋

<p align="left">
  <a href="https://github.com/soumydip">
    <img src="https://komarev.com/ghpvc/?username=soumydip&label=Profile%20Visitors&color=blueviolet&style=flat-square" alt="Profile visitors" />
  </a>
</p>

### 🚀 Full-Stack Developer | Next.js · Node.js · WebSocket · E2EE | B.Tech CSE (2023–2027) | CGPA 8.2

I'm a Computer Science student and backend-focused full-stack developer building production-grade applications with the **MERN stack**, **Next.js**, and **TypeScript**. Right now I'm building **[Ucoder Insights](https://insights.ucoder.in)** — a privacy-first, cookie-free analytics SaaS — alongside real-time systems and open-source tools for the developer community.

> **🌐 Check out my complete work:**
> **[Visit My Portfolio](https://soumyadip.ucoder.in/)** *(My personal portfolio and project showcase)*

---

### 🔥 What I'm Up To

```text
🛠️  Currently Building  →  Ucoder Insights (Analytics SaaS) · Flex Chat (E2EE Messaging)
🌱  Currently Learning  →  SQL/PostgreSQL · System Design · WebRTC
💼  Open To            →  Full-Time Roles · Freelance Projects · Open Source Collabs
⚡  Fun Fact           →  I ship NPM packages from my hostel room 😄
```

---

### 📅 Recent Activity

<!--START_SECTION:activity-->
1. 🚀 Pushed commits to **ucoder_insight_core** — BullMQ queue optimization
2. 🔨 Working on **Flex Chat** — Group E2EE with per-member encrypted keys
3. 📦 Published **ucoder-insight** v1.x on NPM
4. 🐛 Fixed Redis TTL heartbeat bug in real-time presence system
5. 🌐 Deployed **Ucoder Insights** on Azure VM with Docker + Nginx
<!--END_SECTION:activity-->
---

### 💻 Tech Stack & Tools

**Languages & Frontend**

<p align="left">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
</p>

**Backend & Databases**

<p align="left">
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" />
</p>

**DevOps & Tools**

<p align="left">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
</p>

---

### 🏆 Top Projects & Open Source

#### 1. 📊 Ucoder Insights — Full-Stack Analytics SaaS
*Oct 2025 – Present*

A production-grade, **cookie-free analytics SaaS platform** with multi-site tracking, JWT + RBAC auth, and Cloudflare DDoS protection — deployed on Docker + Nginx on Azure VM.

- Published an open-source **NPM package** (JS/TS) for automatic tracking of page views, custom events, scroll depth, geolocation, and JS errors via a single script tag — **GDPR-compliant, zero PII**
- Engineered a **dual-database architecture**: MongoDB time-series collections for raw event ingestion + PostgreSQL (Supabase) for funnel definitions and pre-calculated analytics, with BullMQ-driven event archiving and configurable per-project data retention
- Implemented **Redis caching** and **BullMQ job queues** to handle high event throughput with minimal latency

**Stack:** Next.js · Node.js · MongoDB · PostgreSQL (Supabase) · Redis · BullMQ · Docker · Nginx · Azure · Cloudflare · TypeScript

🔗 **[Live Site](https://insights.ucoder.in)** · **[NPM Package](https://www.npmjs.com/package/ucoder-insight)** · 💻 **[GitHub Repository](https://github.com/soumydip/ucoder_insight_core)**

---

#### 2. 💬 Flex Chat — E2EE Real-Time Messaging Platform
*2026 – Present · Final-Year Team Project*

A **WhatsApp-style secure chat platform** with end-to-end encryption — the server never sees plaintext messages.

- Engineered **E2EE** using Web Crypto API (ECDH key exchange + AES-GCM) with per-member encrypted group keys stored in MongoDB
- Built real-time delivery, typing indicators, and online presence via **Socket.io** and Redis (TTL-based heartbeat)
- Integrated **Transformers.js + IndexedDB** for in-browser multilingual translation (English / Bengali / Hindi) with zero server cost

**Stack:** Next.js · Node.js · Socket.io · MongoDB · Redis · Web Crypto API · ZegoCloud · Transformers.js

---

#### 3. 🌐 Ucoder.in — Freelancing Platform

A fully functional portfolio and freelancing platform to showcase services and manage client projects.

**Stack:** Vite · React · Tailwind CSS · Node.js

🔗 **[Live Website](https://ucoder.in/)** | 💻 Private Repository

---

#### 4. 🎨 Personal Portfolio

A clean, responsive personal portfolio with smooth animations to showcase my projects and skills.

**Stack:** Next.js · TypeScript · Framer Motion

🔗 **[Live Demo](https://soumyadip.ucoder.in/)** | 💻 **[GitHub Repository](https://github.com/soumydip/portfolio)**

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=soumydip&theme=radical&hide_border=true" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=soumydip&layout=compact&theme=radical&hide_border=true&card_width=450" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=soumydip&theme=react-dark&hide_border=true&area=true" alt="Contribution Graph" />
</p>

---

### 🎓 Certifications

- 📜 **Design & Analysis of Algorithms** — NPTEL, IIT Kharagpur
- 📜 **React.js Development** — Ardent Computes Pvt. Ltd.
- 📜 **Python Programming** — Academy of Skill Development
- 📜 **Programming in Java** — NPTEL

---

### 📫 Let's Connect

Feel free to reach out for collaborations, freelance work, or just a quick chat!

- 💼 **LinkedIn:** [Soumyadip Maity](https://www.linkedin.com/in/soumyadip-maity-183ba3310)
- 🐦 **X (Twitter):** [@soumyadip2maity](https://x.com/soumyadip2maity)
- 📧 **Email:** [maitysoumyadip22@gmail.com](mailto:maitysoumyadip22@gmail.com)
- 🌐 **Portfolio:** [soumyadip.ucoder.in](https://soumyadip.ucoder.in/)
- 📦 **NPM:** [ucoder-insight](https://www.npmjs.com/package/ucoder-insight)
