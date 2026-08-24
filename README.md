<div align="center">

# Hi, I'm Aditya Paul 👋
### Full-Stack Developer · 4th year, B.Tech CSE
*I don't just build web apps — I architect systems that scale.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aditya-paul-3774ab416/)

</div>

---

## 🌟 Featured Projects

### [Anivartee](https://github.com/Grizzy100/Anivartee)
`Next.js` `TypeScript` `PostgreSQL` `Prisma` `Node.js` `Redis` `Docker` `Stripe`

> An anti-misinformation platform combating online racism and fake news — users submit viral links for review, and fact-checkers debunk content to build a searchable library of verified evidence.

- 🏗️ **4-service containerized microservices architecture** (User, Post, Points, Payment) with schema-per-service PostgreSQL isolation
- 🔐 Redis-backed JWT rotation and Stripe subscription billing with automated webhook lifecycle handling
- 🏆 Gamified moderation engine — 12-tier ranking system (6 user + 6 fact-checker tiers) with a 30-minute TTL claim system to prevent concurrent reviews
- 📒 Ledger-based points architecture that penalizes inaccuracy over volume

---

### [UniBridge](https://github.com/Grizzy100/UniBridge)
`Node.js` `TypeScript` `Next.js` `PostgreSQL` `Prisma` `RabbitMQ` `Docker` `ChromaDB`

> A 7-service microservices ecosystem replacing fragmented university workflows — mailing, attendance, task management, and AI-powered student support.

- 🏗️ Database-per-service isolation (NeonDB, PostgreSQL schemas) with async event-driven communication via RabbitMQ
- 📧 Category-threaded mailing system with per-participant visibility, replacing legacy Outlook workflows
- 🛡️ Anti-Proxy QR attendance system with 30-second rotating tokens, blocking attendance via `outpass.approved` RabbitMQ events
- 🤖 RAG-powered AI chatbot (ChromaDB + Gemini) for intent-classified, context-aware answers over campus docs

---

### [Kisan-e-Mandi](https://github.com/Grizzy100/Kisan-e-Mandi)
`React.js` `Node.js` `Express` `MongoDB` `Firebase` `Cloudinary` `JWT`

🔗 **Live:** [kisan-e-mandi.vercel.app](https://kisan-e-mandi.vercel.app/)

> A farmer-to-consumer agricultural marketplace with three role-based portals — Admin, Vendor, and Customer.

- 🔑 RBAC enforced via JWT middleware and Firebase Google OAuth
- 🖼️ Cloudinary + Multer for scalable media uploads, Recharts for real-time admin analytics
- ⚡ Fixed a concurrent-like race condition using atomic MongoDB operators (`$addToSet`/`$pull`), eliminating server crashes
- 🚀 Cut ticket submission latency from 3–5s to ~80ms via a fire-and-forget email dispatch utility with retry logic
- 🎨 Optimized rendering with `useCallback`/`useMemo`, route-based code splitting, and Optimistic UI

---


## 🧠 What I Actually Do

I build **end-to-end production-grade platforms** — from pixel-perfect frontends to distributed backend systems built to handle real-world scale. Currently deepening my focus on **microservice architecture, event-driven systems, and cloud infrastructure**.

```
Frontend  →  Backend  →  Infra  →  Scale
   ⛓️         🖥️         🔨        📈
```

---

## 🚧 What I'm Building Next

### [Civic Sethu](https://github.com/adityapaul/civic-sethu) — *In Progress*
> A microservice-based civic grievance platform connecting citizens to municipal corporations across India.

- 🗺️ **Geo-routed complaints** — GPS auto-detects the right municipal body
- 👥 **Role-based dashboards** — Citizen · Field Worker · District Head · State Admin
- ⚙️ **Microservice architecture** — Auth, Routing, Complaints, Notifications, Analytics
- 📡 **Real-time updates** — Live status tracking from report to resolution

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Architecture & DevOps**

![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</div>

---

## 🎯 Engineering Principles

```
✦  Build for failure — design systems that degrade gracefully
✦  Scalability is not optional — it's an architectural decision made on day one
✦  Clean code is a team sport — readable, maintainable, and well-documented
✦  Ship with observability — if you can't measure it, you can't improve it
```

---

## 📫 Let's Connect
